# Face Detection System

This project is a **face detection system** that uses OpenCV's Haar Cascade Classifier and optionally **dlib's HOG-based face detector** to detect human faces in images. It demonstrates classical computer vision techniques for face recognition without requiring deep learning models.

## 🚀 Features
- Detects faces in static images
- Supports both **OpenCV Haar Cascade** and **dlib HOG-based detector**
- Highlights detected faces with bounding boxes
- Easy to extend with eye/smile detection
- Works in Jupyter Notebook

## 🗂️ Project Structure
Face-Detection-System/
│
├── Cascades/
│ └── haarcascade_frontalface_default.xml # Pretrained Haar Cascade model for face detection
│
├── Data Set/
│ └── people1.jpg # Sample image for testing face detection
│
├── face_detection.ipynb # Jupyter Notebook with face detection code
│
├── README.md # Project documentation
│
└── requirements.txt # List of dependencies (OpenCV, dlib, matplotlib, etc.)
## 🛠️ Tech Stack
- **Python 3.x**
- **OpenCV** for face detection using Haar Cascades
- **Matplotlib** for image visualization
- **dlib** (optional) for HOG-based face detection

## 📦 Installation
```bash
# Clone the repository
git clone https://github.com/your-username/Face-Detection-System.git
cd Face-Detection-System

# Create and activate a virtual environment (optional)
conda create -n Face-Detection-System python=3.10
conda activate Face-Detection-System

# Install dependencies
conda install -c conda-forge opencv matplotlib dlib
