# Facial Emotion Detection using Deep Learning

This project implements a **Facial Emotion Recognition System** using **Convolutional Neural Networks (CNNs)** and **OpenCV**.  
It detects human faces from a webcam feed and predicts facial emotions such as **Angry, Disgust, Fear, Happy, Sad, Surprise, and Neutral** in real time.

---

## 📌 Features
- Real-time face detection using OpenCV
- Emotion classification using a trained CNN model
- Uses grayscale facial images (48x48)
- Webcam-based live emotion recognition
- Pre-trained deep learning model for fast inference

---

## 🧠 Model Details
- Model Type: Convolutional Neural Network (CNN)
- Input Shape: `(48, 48, 1)`
- Output Classes: 7 emotions
- Framework: TensorFlow / Keras
- Model Files:
  - `facialemotionmodel.json` → Model architecture
  - `facialemotionmodel.h5` → Trained weights

---

## 📂 Project Structure
cvproject/
│
├── asl.py # Loads the trained model
├── detect.py # Real-time emotion detection script
├── facialemotionmodel.json # CNN model architecture
├── facialemotionmodel.h5 # Model weights
├── haarcascade_frontalface_default.xml
├── README.md


---

## ⚙️ Requirements

> ⚠️ Important: This project requires **Python 3.8 or 3.9**

### Python Libraries
```bash
tensorflow==2.10.0
keras==2.10.0
opencv-python
numpy
pandas
scikit-learn
tqdm
