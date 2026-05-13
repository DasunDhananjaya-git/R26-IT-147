# R26-IT-147 - NeoRider

## IoT–ML Intelligent Rider Training & Safety System with Digital Route Twin

NeoRider is an intelligent motorcycle rider training and safety platform designed for beginner and learner riders. The system combines IoT sensors, machine learning, real-time safety monitoring, mobile application support, and digital route twin concepts to improve rider awareness, detect risky riding behavior, and support safer motorcycle training.

---

## 🚀 Project Overview

Motorcycle accidents are a major cause of road injuries and fatalities, especially among young and beginner riders. Existing motorcycle safety systems mostly focus on accident detection after a crash, while NeoRider focuses on preventive safety monitoring before accidents happen.

NeoRider helps riders, trainers, and safety organizations by providing real-time monitoring, unsafe behavior detection, road-sign-aware guidance, rider behavior analytics, and mobile-based feedback.

---

## 🎯 Main Objectives

- Detect unsafe rider posture and riding behavior in real time
- Monitor rider movement using IMU sensor data
- Provide intelligent alerts for risky riding conditions
- Support beginner riders during training sessions
- Analyze rider behavior and generate safety scores
- Provide road-sign-aware and context-aware guidance
- Build a digital route twin for rider training and performance analysis

---

## 🧠 Key Features

### Smart Helmet & Rider Safety Monitoring
- Dual IMU monitoring using helmet and chest/body sensors
- Real-time telemetry data collection
- Unsafe posture detection
- Sudden movement and imbalance detection
- Real-time safety alerts through the mobile application

### Road-Sign-Aware Guidance System
- Road sign detection using a YOLO-based model
- Context-aware guidance based on riding conditions
- Rider-friendly guidance messages
- Low-speed assistance for learner riders
- Mobile interface for displaying detected signs and guidance

### Behavior Analytics & Scoring Engine
- Rider behavior classification
- Safety score generation
- Detection of riding patterns such as smooth, aggressive, unstable, and harsh braking
- Machine learning based behavior prediction
- Performance feedback for novice motorcyclists

### Digital Route Twin
- Route recording
- Geo-tagging
- Risk zone identification
- Performance analysis
- Training replay support

---

## 🏗️ System Architecture

NeoRider consists of the following main layers:

1. **Hardware Layer**
   - Smart helmet
   - IMU sensors
   - Chest/body sensor unit
   - Optional camera module
   - Bluetooth/Wi-Fi communication

2. **Backend Layer**
   - FastAPI backend
   - Real-time data processing APIs
   - Prediction APIs
   - Firebase integration
   - Cloud synchronization

3. **Machine Learning Layer**
   - Feature extraction from sensor data
   - Rider behavior classification
   - Risk prediction
   - Safety score calculation
   - Models such as Random Forest, XGBoost, and LightGBM

4. **Mobile Application Layer**
   - Flutter mobile app
   - Rider dashboard
   - Real-time alerts
   - Telemetry visualization
   - Route and training history
   - Profile and safety insights

5. **Cloud & Database Layer**
   - Firebase authentication
   - Firestore database
   - Cloud storage
   - Real-time updates

---

## 🛠️ Technology Stack

| Area | Technologies |
|---|---|
| Mobile App | Flutter |
| Backend | FastAPI, Python |
| Database | Firebase Firestore |
| Cloud | Firebase |
| Machine Learning | Random Forest, XGBoost, LightGBM |
| IoT Sensors | IMU Sensors, ESP32/Arduino-based units |
| Computer Vision | YOLO |
| Design | Figma |
| Data | Public IMU datasets + custom rider datasets |

---

## 📱 Mobile Application Modules

- User authentication
- Rider dashboard
- Real-time telemetry view
- Live alerts
- Ride history
- Route tracking
- Road sign prediction result view
- Behavior score view
- Profile and settings
- Emergency/SOS support

---

## 🤖 Machine Learning Components

NeoRider uses ML models to analyze rider behavior and predict safety risks.

### ML Tasks

- Unsafe posture detection
- Riding behavior classification
- Harsh braking detection
- Imbalance detection
- Risk score prediction
- Road sign detection

### Example Behavior Classes

- Smooth
- Aggressive
- Unstable
- Harsh braking
- Unsafe posture

---

## 👥 Target Users

- Beginner motorcycle riders
- Learner riders
- Riding schools and training institutes
- Parents and guardians
- Traffic safety organizations
- Delivery rider fleets
- Insurance and smart mobility sectors

---

## 🌟 Novelty of the Project

NeoRider is different from traditional rider safety systems because it combines rider training and preventive safety monitoring into one intelligent ecosystem.

### Unique Contributions

- Smart helmet integration
- Dual IMU sensor monitoring
- ML-based rider behavior prediction
- Real-time alert system
- Digital route twin for rider training
- Road-sign-aware guidance
- Rider safety and rider training combined in one platform
- Preventive safety approach instead of only accident detection

---

## 📊 Expected Outcomes

- Improved rider safety awareness
- Reduced risky riding behavior
- Better training support for beginner riders
- Real-time feedback during riding sessions
- Data-driven rider performance analysis
- Scalable smart safety platform for riding schools and fleets

---

## 💼 Commercialization Potential

NeoRider can be commercialized as a smart rider safety and training platform.

### Possible Revenue Models

- Smart helmet sales
- Monthly subscription for premium rider analytics
- Riding school partnerships
- Fleet safety packages
- Training platform licensing
- Insurance company collaborations

---

## 🗺️ Future Enhancements

- Advanced digital route simulation
- More accurate ML models with larger datasets
- Full hardware prototype integration
- Real-time video-based road sign detection
- Insurance-based rider risk scoring
- Supervisor dashboard for riding schools
- AI-based personalized rider feedback
- International market expansion

---

## 👨‍💻 Research Group

**Group ID:** R26-IT-147  
**Project Name:** NeoRider  
**Specialisation:** Information Technology  
**Research Cluster:** AIMS  

### Members

- Gamage DMDI
- Wickramasinghe G.G.D.D
- Thilakarathna T.T

---

## 📌 Project Title

**NeoRider - IoT–ML Intelligent Rider Training & Safety System with Digital Route Twin**

---

## 📄 License

This project is developed for academic and research purposes.
