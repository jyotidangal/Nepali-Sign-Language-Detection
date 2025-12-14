
# 🖐️ Nepali Sign Language Detection System

A **deep learning–powered real-time Nepali Sign Language (NSL) detection system** designed to bridge communication gaps between the hearing-impaired community and the general public in Nepal.

---

## 📌 Overview

This project detects **static Nepali sign language alphabets (Ka–Gyan)** and **commonly used words** using a webcam. It provides **real-time text and audio output**, enabling inclusive and accessible communication.

---

## 🚀 Features

* ✅ Real-time hand gesture detection using webcam
* ✅ CNN-based classification for high accuracy
* ✅ Character-level (Ka–Gyan) recognition
* ✅ Word-level gesture recognition (e.g., *Namaskar, Ghar, Ma, Dhanyabaad*)
* ✅ Text-to-Speech (TTS) output
* ✅ React frontend + Django REST backend
* ✅ Custom-trained dataset (~1,000 images per class)

---

## 🧠 Model Architecture

* **Character Recognition Model:** `ka_to_gyan_model.h5`
* **Word Recognition Model:** `gesture_model.h5`
* **Framework:** Convolutional Neural Network (CNN)
* **Optimization:** Dropout layers & Early Stopping
* **Accuracy:** > **99% validation accuracy**

---

## 🛠️ Tech Stack

* **Programming Language:** Python 3.10+
* **Deep Learning:** TensorFlow / Keras
* **Computer Vision:** OpenCV, MediaPipe
* **Backend:** Django, Django REST Framework
* **Frontend:** React
* **Others:** NumPy, Pillow, Text-to-Speech (TTS)

---

## ⚙️ System Workflow

1. Capture live video via webcam
2. Detect hand landmarks using MediaPipe
3. Extract Region of Interest (ROI)
4. Preprocess image (resize, normalize)
5. Predict gesture using trained CNN
6. Display text and generate audio output

---

## 📂 Project Structure

```
├── models/
│   ├── ka_to_gyan_model.h5
│   └── gesture_model.h5
├── backend/ (Django)
├── frontend/ (React)
├── dataset/
├── requirements.txt
└── README.md
```

---

## 🧪 Testing

* Unit Testing
* Integration Testing
* Real-time webcam validation

---

## ⚠️ Limitations

* Supports only **static gestures**
* Limited vocabulary
* Performance may degrade in poor lighting
* Dynamic gestures not supported yet

---

## 🔮 Future Enhancements

* 🔹 Dynamic gesture recognition
* 🔹 Sentence-level translation
* 🔹 Transfer learning (MobileNet, ResNet)
* 🔹 Multilingual audio output (Nepali, English, Hindi)

---

## 👥 Team Members

* **Ashim Pokharel** – Literature review, documentation, system design, coding
* **Jyoti Dangal** – Feature analysis, objectives, ER diagram, architecture, testing( Project Leader)
* **Renu Singh** – Problem analysis, DFD, GUI design, integration testing

