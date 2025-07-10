# AI-Driven Smart Helmet System with Simulation for Enhanced Rider Safety

This project presents an innovative AI-integrated smart helmet designed to improve rider safety through real-time monitoring, intelligent decision-making, and hands-free interaction. The system is powered by machine learning, computer vision, speech analysis, and IoT technologies.

## 🧠 Key Features

- **Alcohol Detection via Speech** using CNN + LSTM (99.98% accuracy)
- **Drowsiness Detection** using Haar Cascade + CNN (98.89% accuracy)
- **Accident Detection** using YOLOv8 + Vision Transformers (ViT) (99.76% accuracy)
- **AI Voice Assistant** with Gemini API (online) and Mistral LLM (offline)
- **Real-time Navigation** with Google Maps API (online) and OSRM (offline)
- **Emergency Alerts** via Twilio with real-time GPS location
- **Simulation Mode** for testing and analysis

## 📦 Modules Overview

### 1. User Interface Module
- Voice input for alcohol detection and AI commands
- Camera input for drowsiness and accident monitoring
- GPS tracking for navigation and emergency alerts

### 2. Processing Module
- Deep learning models for detection and classification
- Speech processing with MFCC & spectrogram analysis
- Real-time accident prediction using YOLOv8 and ViT

### 3. Output Module
- Audio and UI alerts
- SMS/email notifications
- Voice feedback via AI Assistant

## 🛠️ Tech Stack

### Languages & Libraries
- **Python**
- **OpenCV**, **TensorFlow**, **Keras**
- **YOLOv8**, **CNN**, **LSTM**, **ViT**
- **DeepSpeech**, **Whisper**
- **Google Maps API**, **OpenStreetMap**
- **Twilio**, **Gemini API**, **Mistral LLM**

### Hardware Requirements
- Microphone, Webcam
- 16GB RAM, Multi-core CPU or GPU
- Internet/WiFi for online features

## 🔍 System Architecture

- Simulated Sensor Input → Data Preprocessing → ML Models → Inference → Alerts/UI
- Supports both **online** (cloud AI) and **offline** (edge processing) modes

## 🧪 Accuracy & Results

| Module                | Model Used          | Accuracy   |
|----------------------|---------------------|------------|
| Alcohol Detection     | CNN + LSTM          | 99.98%     |
| Drowsiness Detection  | Haar + CNN          | 98.89%     |
| Accident Detection    | YOLOv8 + ViT        | 99.76%     |

## 📍 Emergency & Safety

- Sends **real-time location** to emergency contacts during accidents
- Disables ignition when intoxicated speech is detected
- Alerts for drowsiness through buzzer + notifications

## 🧩 Functional Highlights

- Offline AI Assistant fallback in low connectivity areas
- Multimodal safety detection (audio + video + sensor fusion)
- Realtime route planning + restricted zone alerts
- Seamless integration with third-party APIs for communication and navigation

## 📈 Future Enhancements

- Integration with real-time emergency services
- EEG and biometric sensor support
- Hardware-optimized deep learning inference
- Expanded deployment for logistics/military use cases

## 📑 Authors
 
- Sai Nishwanth Valiveti (21241A3251)  

---

© 2025 GRIET - Computer Science and Business Systems Department
