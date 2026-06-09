# AI-Based IoT System for Non-Destructive Ripeness Detection in Brown-Bagged TomEJC Mangoes

QualityQuest is an AI-powered IoT system that evaluates the quality and ripeness of brown-bagged TomEJC mangoes without causing physical damage. By integrating smart sensors, machine learning, cloud services, and a Flutter mobile application, the system provides real-time insights into mango quality.

---

## 🎯 Key Features

### 🥭 Ripeness Detection
Classifies mangoes as **Raw** or **Ripe** using multi-sensor data and machine learning models.

### 🍬 Sugar & Acidity Estimation
Predicts internal sugar content and acidity levels without cutting the fruit.

### ⏳ Time-to-Consume Prediction
Estimates the optimal consumption period for the best eating quality.

### ❤️ Health Recommendations
Provides personalized consumption advice based on:
- Ripeness Level
- Sugar Content
- Mango Weight
- Diabetes Status

---

## 🔬 Hardware Components

| Component | Purpose |
|------------|----------|
| ESP32 | Main Controller |
| AS7263 NIR Sensor | Sugar & Acidity Estimation |
| BME688 Gas Sensor | Aroma/VOC Detection |
| MPU6050 | Firmness Estimation |
| Load Cell + HX711 | Weight Measurement |
| Servo Motor | Controlled Tapping Mechanism |

---

## 🤖 Machine Learning

The system uses multi-sensor data fusion and machine learning techniques to predict mango quality.

### Models Evaluated

- Random Forest
- Support Vector Machine (SVM)
- Artificial Neural Network (ANN)

### Evaluation Metrics

- Accuracy
- Precision
- Recall
- F1-Score
- ROC-AUC

---

## 📱 Mobile Application

A Flutter-based mobile application displays:

- Sensor Readings
- Ripeness Predictions
- Sugar & Acidity Estimates
- Time-to-Consume Predictions
- Personalized Health Recommendations

---

## 🛠 Technologies Used

### Frontend
- Flutter
- Dart

### Backend
- Python
- REST API

### Machine Learning
- Scikit-learn
- TensorFlow
- Pandas
- NumPy

### Database
- MySQL

### Cloud Services
- AWS

### Hardware & IoT
- ESP32
- Arduino IDE

---

## 🚀 System Architecture

<p align="center">
  <img src="Images/system_workflow.jpg" alt="System Workflow" width="850">
</p>

---

## 👥 Team Project

This project was developed as an undergraduate research and development project focusing on the application of Artificial Intelligence, Internet of Things (IoT), and Machine Learning for non-destructive fruit quality assessment.

---

## 📜 License

This project is intended for educational and research purposes.
