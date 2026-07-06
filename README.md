# 🛰️ ISRO Craters and Boulders Detection Project

A professional **Space Image Analysis Project** that detects and analyzes **craters** and **boulders** from planetary surface images.

This project is designed for academic demonstration, research practice, and GitHub portfolio use. It focuses on identifying important surface features that are useful in planetary exploration, lunar mapping, landing-site analysis, and terrain understanding.

---

## 📌 Project Overview

Planetary surface analysis is an important part of space exploration. Craters and boulders provide useful information about surface age, terrain roughness, impact history, geological structure, and landing safety.

This project helps analyze planetary or lunar surface images and identify two major surface features:

- **Craters**
- **Boulders**

The system can be used for studying lunar terrain images and supporting automated terrain understanding for space mission-related analysis.

---

## 🚀 Features

- Detect craters from planetary surface images
- Detect boulders from terrain images
- Upload and analyze space surface images
- Display processed detection output visually
- Show detected object count
- Support image preprocessing
- Suitable for ISRO-themed academic project demonstration
- GitHub-ready project structure
- Easy to understand, run, and extend

---

## 🛰️ Problem Statement

During lunar and planetary missions, surface analysis is critical for:

- Safe landing-site selection
- Rover navigation
- Terrain hazard detection
- Geological study
- Surface age estimation
- Mission planning

Manual identification of craters and boulders from high-resolution planetary images is time-consuming. This project aims to automate or simplify the detection process using image processing and computer vision techniques.

---

## 🛠️ Technologies Used

- Python
- OpenCV
- NumPy
- Matplotlib
- Streamlit
- Pillow
- Image Processing
- Computer Vision

---

## 📁 Project Structure

```text
isro_craters_boulders_project/
│
├── app/
│   └── app.py
│
├── src/
│   ├── crater_detection.py
│   ├── boulder_detection.py
│   ├── image_processing.py
│   └── utils.py
│
├── dataset/
│   ├── craters/
│   ├── boulders/
│   └── test_images/
│
├── outputs/
│   ├── detected_craters/
│   ├── detected_boulders/
│   └── results/
│
├── assets/
│   └── sample_images/
│
├── requirements.txt
├── README.md
└── .gitignore
