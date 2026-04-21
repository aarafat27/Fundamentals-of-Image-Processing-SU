# Fundamentals of Image Processing — Laboratory Works

**Student:** Arafat Islam  
**University:** Sorbonne University  
**Course:** Fundamentals of Image Processing  
**Track / Program:** IMA  

<img width="1790" height="990" alt="image" src="https://github.com/user-attachments/assets/4bb9aa8d-87d2-45b1-9681-3310c48605b5" />


## Overview

This repository contains my laboratory work for the **Fundamentals of Image Processing** course at **Sorbonne University**. The practical sessions cover the main foundations of modern image processing, from basic image manipulation to frequency analysis, filtering edge and corner detection, segmentation, content-based image retrieval and face recognition.

The work is organized as a collection of Jupyter notebooks. Each notebook corresponds to one lab session, except the last notebook which combines **Labs 9 and 10**.

<img width="1965" height="789" alt="image" src="https://github.com/user-attachments/assets/46cbc517-4de8-48e3-860a-ade5508a95bf" />


## Repository Contents

```text
.
├── ima_lab_1_Arafat.ipynb
├── ima_lab_2_Arafat.ipynb
├── ima_lab_3_Arafat.ipynb
├── ima_lab_4_Arafat.ipynb
├── ima_lab_5_Arafat.ipynb
├── ima_lab_6_Arafat.ipynb
├── ima_lab_7_Arafat.ipynb
├── ima_lab_8_Arafat.ipynb
└── ima_lab_9_10_Arafat.ipynb
```

<img width="2249" height="790" alt="image" src="https://github.com/user-attachments/assets/35511a89-1d26-495d-a5a9-c876c9fb631b" />


## Lab Summary

### Lab 1 — Introduction and Image Enhancement
This lab introduces the Python tools used throughout the course, especially **NumPy**, **Matplotlib**, and basic image manipulation with **PIL**. It focuses on image enhancement techniques such as normalization and intensity transformation.

**Main topics:**
- NumPy arrays and indexing
- Image loading and display
- Dynamic range manipulation
- Intensity normalization
- Basic enhancement operations

---

### Lab 2 — Fourier Transform
This lab studies the **2D Fourier transform** and its application to image analysis. It explores how translation, rotation, and other geometric changes affect the frequency representation of an image.

**Main topics:**
- 2D discrete Fourier transform
- Magnitude spectrum visualization
- Frequency-domain interpretation
- Effects of image rotation and translation in the Fourier domain

---

### Lab 3 — 2D Sampling and Aliasing
This lab investigates the sampling of 2D signals and the phenomenon of **aliasing**. Synthetic patterns and natural images are used to understand the impact of insufficient sampling and the Shannon–Nyquist criterion.

**Main topics:**
- 2D sinusoidal signals
- Sampling on regular grids
- Aliasing effects
- Subsampling of natural images
- Frequency interpretation of sampled images

---

### Lab 4 — Frequency Filtering and Color
This lab focuses on filtering in both the spatial and frequency domains. It also introduces the handling of color images and the role of anti-aliasing filtering before subsampling.

**Main topics:**
- Frequency filtering
- Linear filtering by convolution
- Smoothing and sharpening filters
- Anti-aliasing before subsampling
- RGB image representation and manipulation

---

### Lab 5 — Edge Detection
This lab studies **edge detection** using first-order and second-order operators. It also examines the role of smoothing and introduces non-maximum suppression for thin and accurate edges.

**Main topics:**
- First-order edge detectors
- Second-order edge detectors
- Gradient computation
- Laplacian-based detection
- Non-maximum suppression
- Influence of smoothing on edge localization

---

### Lab 6 — Harris Corner Detector
This lab is dedicated to the **Harris corner detector**, a classical method for detecting interest points in images. The implementation studies the Harris response and the invariance properties of the detector.

**Main topics:**
- Harris response computation
- Corner extraction
- Gradient-based structure analysis
- Interest point detection
- Detector behavior under image transformations

---

### Lab 7 — Split and Merge Segmentation
This lab implements the **split and merge** segmentation algorithm. The method recursively divides an image into regions and merges neighboring regions according to a homogeneity criterion.

**Main topics:**
- Region-based segmentation
- Recursive splitting
- Neighbor analysis
- Merging predicates
- Region representation and visualization

---

### Lab 8 — Color Quantization and Content-Based Image Search
This lab develops a simple **content-based image retrieval (CBIR)** pipeline based on color information. Images are described using HSV histograms, and pairwise similarity is used to retrieve visually similar images.

**Main topics:**
- Color quantization
- HSV color space
- Histogram descriptors
- Similarity computation between images
- Search by visual content

---

### Labs 9 & 10 — Face Recognition by Eigenfaces
The final notebook combines two practical sessions on **face recognition** using the **Eigenfaces** method based on **Principal Component Analysis (PCA)**. The system is used for face representation, reconstruction, identification, and face/non-face discrimination.

**Main topics:**
- Loading and centering a face database
- Average face computation
- PCA / Eigenfaces
- Projection into face subspace
- Reconstruction from principal components
- Identification by nearest neighbor in Eigenface space
- Face vs non-face classification using reconstruction error

<img width="1780" height="593" alt="image" src="https://github.com/user-attachments/assets/5a2eeadf-8f9c-4217-819a-8ec9a3fb4168" />


## Learning Outcomes

Through these laboratory works, the following skills were developed:

- Practical manipulation of grayscale and color images
- Understanding of image representation in spatial and frequency domains
- Implementation of core image processing algorithms from scratch
- Analysis of enhancement, filtering, and sampling effects
- Detection of edges, corners, and segmented regions
- Construction of simple visual descriptors for image retrieval
- Application of dimensionality reduction to face recognition

---

## Tools and Libraries

The notebooks mainly rely on the following Python libraries:

- `numpy`
- `matplotlib`
- `scipy`
- `Pillow`
- `jupyter`

Depending on the notebook, additional helper libraries may also be used for numerical operations and image display.

---

## How to Run

### 1. Install dependencies

```bash
pip install numpy matplotlib scipy pillow jupyter
```

### 2. Launch Jupyter Notebook

```bash
jupyter notebook
```

### 3. Open the notebook you want to run
For example:

```bash
jupyter notebook ima_lab_1_Arafat.ipynb
```

or

```bash
jupyter notebook ima_lab_9_10_Arafat.ipynb
```

---

## Notes

- Some notebooks use external image files or datasets expected to be present in the working environment.
- Labs 9 and 10 are grouped together in a single notebook.
- The notebooks contain both code and written comments explaining the methodology and observed results.

---

## Conclusion

This collection of laboratory works presents a progressive exploration of the main concepts of image processing. Starting from image enhancement and Fourier analysis, the course advances toward filtering, feature detection, segmentation, retrieval, and recognition.

Taken together, these notebooks form a practical portfolio of classical image processing methods and illustrate how theoretical concepts can be translated into concrete implementations in Python.

---

## Author

**Arafat Islam**  
Sorbonne University  
Fundamentals of Image Processing
