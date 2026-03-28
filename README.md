# 😷 Face Mask Detection System using OpenCV, PCA, and SVM

A real-time **Face Mask Detection System** built using **Python**, **OpenCV**, **NumPy**, **Scikit-learn**, **PCA**, and **Support Vector Machine (SVM)**.  
This project detects human faces through a webcam and classifies whether the person is **wearing a mask** or **not wearing a mask**. Based on the prediction, the system displays a message such as:

- **Door is open** → if at least one detected face is wearing a mask
- **Please wear a mask** → if no mask is detected

This project demonstrates the practical use of **Machine Learning**, **Computer Vision**, and **Real-Time Video Processing**.

---

## 📌 Project Overview

The COVID-19 pandemic increased the importance of automated safety systems in public and private spaces.  
This project aims to create a **real-time mask detection system** that can be integrated with smart access systems such as:

- Office entry systems
- College/school entry gates
- Labs and restricted areas
- Public service counters
- Smart attendance systems

The system uses:

- **Haar Cascade Classifier** for face detection
- **PCA (Principal Component Analysis)** for dimensionality reduction
- **SVM (Support Vector Machine)** for classification

---

## 🚀 Features

- Real-time webcam-based face detection
- Face mask / no-mask classification
- Uses **Machine Learning** instead of deep learning (lightweight approach)
- Dimensionality reduction using PCA for faster processing
- Displays bounding box around detected faces
- Shows prediction label on the video frame
- Simple door access logic:
  - If mask detected → **Door is open**
  - Else → **Please wear a mask**
- High classification accuracy on test data (**97.85%**)

---

## 🛠️ Tech Stack

### Programming Language
- Python

### Libraries Used
- **NumPy** → For handling image datasets
- **OpenCV (cv2)** → For webcam access, face detection, and image processing
- **Scikit-learn** → For PCA, train-test split, SVM model, and evaluation

### ML Techniques
- **PCA (Principal Component Analysis)** → Reduces image dimensionality
- **SVM (Support Vector Machine)** → Classifies mask vs no-mask images

---

## 📂 Project Structure

```bash
Face-Mask-Detection/
│
├── with_mask.npy
├── without_mask.npy
├── haarcascade_frontalface_default.xml
├── face_mask_detection.py
├── README.md
└── screenshots/
    ├── mask_detected.png
    ├── no_mask_detected.png
