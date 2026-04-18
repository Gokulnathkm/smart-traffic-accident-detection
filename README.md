# 🚗 Smart Traffic Accident Detection System

An AI-powered deep learning project that detects road accidents from uploaded traffic videos using **EfficientNet-B0 + LSTM**.
The system analyzes video frames, predicts accident probability, triggers an alarm, and displays results in an interactive dashboard.

---

## 📌 Project Overview

Road accidents are a major safety issue. Manual CCTV monitoring is difficult and time-consuming.
This project automates accident detection using computer vision and deep learning.

The system classifies traffic videos into:

* Accident
* Non Accident

It also provides:

* Confidence graph
* Alarm alert
* Summary statistics
* Premium UI dashboard

---

## 🎯 Objectives

* Detect accidents automatically from traffic videos
* Reduce manual monitoring effort
* Provide fast emergency alerts
* Improve road safety using AI
* Build an interactive dashboard

---

## 🧠 Model Used

### EfficientNet-B0

Used for extracting spatial features from video frames.

### LSTM

Used for learning temporal patterns across frame sequences.

### Why This Combination?

* EfficientNet gives strong image classification performance
* LSTM understands motion and frame continuity
* Better than using only CNN for video data

---

## 📂 Dataset Structure

data/
├── train/
│   ├── Accident/
│   └── Non Accident/
├── val/
│   ├── Accident/
│   └── Non Accident/
└── test/
├── Accident/
└── Non Accident/

---

## ⚙️ Technologies Used

* Python
* PyTorch
* OpenCV
* NumPy
* Matplotlib
* Gradio
* Google Colab
* GitHub

---

## 🔄 Workflow

1. Upload video
2. Extract frames
3. Resize and normalize frames
4. Create frame sequences
5. Pass frames to EfficientNet-B0
6. Pass extracted features to LSTM
7. Predict Accident / Non Accident
8. Show confidence graph
9. Trigger alarm if accident detected
10. Display dashboard results

---

## 🧹 Preprocessing

* Frame extraction from videos
* Resize to 224x224
* Normalization
* Sequence creation
* Train / Validation / Test split

### Data Augmentation

* Horizontal Flip
* Rotation
* Brightness Adjustment
* Affine Transform

---

## 📊 Features

* 🎥 Video Upload
* 🤖 AI Prediction
* 📈 Confidence Graph
* 🚨 Alarm Alert
* 📋 Summary Panel
* 🌙 Premium Dashboard UI

---

## 📈 Performance

* High validation accuracy achieved during training
* Real-time prediction support
* Works on Google Colab CPU/GPU

---

## 🚀 Future Enhancements

* Live CCTV integration
* Emergency service auto notification
* GPS accident location tracking
* Multi-camera monitoring
* Cloud deployment
* Mobile app support


## 📌 Conclusion

This project demonstrates how AI can improve traffic monitoring by automatically detecting accidents from videos.
By combining EfficientNet-B0 and LSTM, the system captures both image details and motion patterns, making accident detection smarter and faster.
