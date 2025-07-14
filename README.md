# Occlusion-Aware Face Recognition Under Face Mask Conditions

This repository contains the source code, documentation, and model assets for the project titled:

**Occlusion-Aware Face Detection and Landmark-Based Matching Under Face Mask Conditions Using CNN and OpenCV**

This work was conducted as part of a final year research project at Coventry University and is prepared for academic publication in MDPI *Sensors*.

---

##  Overview

Traditional facial recognition systems struggle under partial occlusion—especially when users wear face masks. This project introduces a **hybrid face recognition pipeline** that combines:

- **CNN-based mask detection**
- **Geometric feature matching** using facial landmarks (Euclidean & Cosine similarity)
- **Real-time processing** with OpenCV and Dlib

The system dynamically selects a recognition path based on mask presence and performs accurate identity matching using the upper face region.

---

##  Key Features

- Mask vs. no-mask classification using a trained CNN
- Landmark extraction (68-point detection focused on eyes, nose bridge, and eyebrows)
- Lightweight geometric feature matching (suitable for real-time systems)
- Modular Python pipeline for testing and extension
- Evaluation metrics for precision, recall, F1-score, and accuracy

---

##  Why Use This Project?

- **Real-world relevance**: Built for environments where face masks are common (e.g., healthcare, airports, surveillance).
- **Efficient and modular**: Combines machine learning and classical computer vision with low computational overhead.
- **Open and extensible**: Use this as a template for occlusion-aware biometric applications or augment it with deep learning.

---

##  Datasets

This project uses the following publicly available datasets:

1. **MDMFR (Masked Face Recognition Dataset)**  
    [Zenodo Link](https://doi.org/10.5281/zenodo.6408603)

2. **COMASK20 Dataset**  
    [GitHub – Vu et al.](https://github.com/tuminguyen/COMASK20
)) *(please insert actual dataset repo link)*

---

##  Installation

Clone the repository and install dependencies:

```bash
git clone https://github.com/KwasiKodie/occlusion-aware-face-recognition.git
cd occlusion-aware-face-recognition
pip install -r requirements.txt
