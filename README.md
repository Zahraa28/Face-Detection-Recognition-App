# 👤 Face Detection & Recognition App

## 📌 Project Overview
This is **Project 4/6** of the Applied AI Lab series.  
The goal was to build a **face detection and recognition system** using deep learning models and deploy it in a simple **Flask web app**.

---

## ⚙️ Methods & Workflow
### 1. Face Detection with MTCNN
- Used `facenet_pytorch` pre-trained MTCNN model
- Detects:
  - Bounding boxes
  - Probabilities of being a face
  - Facial landmarks (eyes, nose, mouth)

### 2. Face Recognition with Inception-ResNet V1
- Extracts faces from MTCNN
- Converts each face into **embeddings**
- Compares embeddings → closer = same person

### 3. Flask Web App
- Upload an image → detect & recognize faces
- Simple frontend with HTML + CSS
- Backend logic in Python with Flask

---

## 📂 Dataset
- Extracted frames from YouTube videos
- Sample test images provided

---
### Contact

**Zahraa**
📧 alzahramohamed28@gmail.com

