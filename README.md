# Hand-gesture-datasets
# ✋ Hand Gesture Recognition System

## 📌 Overview

This project implements a **real-time hand gesture recognition system** using computer vision and machine learning.

## 🎯 Objective

To detect and classify hand gestures from webcam input for human-computer interaction.

---

## 🧠 Approach

* Hand detection using MediaPipe
* Feature extraction using 21 hand landmarks
* Classification using Random Forest

---

## 📂 Project Structure

```
dataset/
   thumbs_up/
   peace/
   fist/

train_gesture_model.py
gesture_prediction.py
gesture_model.pkl
README.md
```

---

## ⚙️ Installation

```bash
pip install opencv-python mediapipe scikit-learn numpy
```

---

## ▶️ Usage

### 1. Train Model

```bash
python train_gesture_model.py
```

### 2. Run Real-Time Prediction

```bash
python gesture_prediction.py
```

---

## 📊 Features

* Real-time gesture detection
* Works with webcam
* Lightweight and fast
* Easy to extend with new gestures

---

## 📈 Example Gestures

* 👍 Thumbs Up
* ✌️ Peace
* ✊ Fist

---

## 🔮 Future Improvements

* Deep learning (CNN/LSTM)
* More gesture classes
* Mobile app integration
* Gesture-based system control

---

## 📜 License

Open-source and free to use.
