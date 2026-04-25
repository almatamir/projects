## 🚀 Projects

### 🎵 Image Classification & Music Recommendation

Built an end-to-end deep learning pipeline that classifies photos and recommends music for Instagram stories. Designed a hierarchical architecture where a parent model (ResNet50V2) identifies broad scene categories and specialist sub-models refine predictions into subcategories. Addressed real-world ML challenges including overfitting (dropout, L2 regularization, early stopping), class imbalance (class-weighted training), and custom dataset construction via Unsplash API. Classification output is passed to Google Gemini AI to generate contextual song recommendations, served via a REST API.
**Tech**: Python, TensorFlow, Keras, ResNet50V2, Flask, Google Gemini API, OpenCV
---

🔗 https://github.com/almatamir/photo-mood-classifier

---

### ☁️ Cloud Computing & Software Engineering

Designed and deployed a microservices-based REST API for pet inventory management. The system is containerized with Docker and Docker Compose, uses an NGINX reverse proxy for load balancing, and includes a fully automated CI/CD pipeline with GitHub Actions and Pytest.
**Tech:** Flask, MongoDB, Docker, Docker Compose, NGINX, GitHub Actions, Pytest
---

🔗 https://github.com/almatamir/pet-store-microservices

---

### 🏓 AI Table Tennis Analyzer

Built a multi-module computer vision pipeline for table-tennis broadcast analysis:    
real-time player tracking (YOLOv8 + ByteTrack), pose-based shot classification 
(forehand/backhand/smash via wrist velocity peak detection), scoreboard OCR (EasyOCR),
and progressive heatmap generation. Outputs annotated video with live score overlay 
and shot labels. 
**Tech:** Python, YOLOv8, EasyOCR, OpenCV, SciPy
---

🔗 https://github.com/almatamir/tt-vision

---

### 🤖 Face Recognition Telegram Bot

Built an asynchronous identity verification system using facial recognition. Implemented a computer vision pipeline that extracts 128-dimensional embeddings and matches faces using Euclidean distance.
**Tech:** Python, face_recognition, Telegram API, Computer Vision
---

🔗 https://github.com/almatamir/face-recognition-bot.git
