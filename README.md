# 🚗 FedEx Fleet Monitoring & Driver Safety System  

## Overview  
This project was developed during my **Research & Development Internship at HILCPS Lab, IIT Madras**, in collaboration with **FedEx**. It focuses on **real-time driver monitoring, vehicle health tracking, and fleet analytics** using **Flutter, Computer Vision, ML, and Embedded Systems**.  

The system consists of:  
- **Flutter App (Mobile) ** – Real-time driver monitoring, vehicle diagnostics, and alerts.  
- **Admin Dashboard (Web) ** – Fleet tracking, weekly/monthly reports, and AI-driven insights.  
- **Backend (WebSocket & PostgreSQL) ** – Data ingestion, real-time storage, and analytics.  

## Tech Stack  
- **Programming:** Python, Dart, SQL  
- **Machine Learning & Computer Vision:** OpenCV, Dlib, MediaPipe, NumPy  
- **Deep Learning Models:** CNN, RNN, LSTM  
- **NLP & AI Techniques:** Gaze Tracking, Facial Landmark Detection, Pose Estimation  
- **Frameworks & Tools:** Flutter, Flask, PostgreSQL, WebSockets, ELM327 (OBD-II), Docker  

##  Techniques Used  
### 🔹 **Driver Monitoring & Safety (Computer Vision & ML)**  
- **Drowsiness Detection** using:  
  - Eye Aspect Ratio (**EAR**) – Detects eye closure duration.  
  - Mouth Aspect Ratio (**MAR**) – Identifies yawning frequency.  
- **Distraction Detection** using:  
  - **Yaw, Pitch, Roll** – Measures head movement angles.  
  - **Gaze Points Tracking** – Determines if the driver is looking away.  
- **Combined these features** to provide **real-time alerts with audio & emojis** 🚨🎵😴.  

### 🔹 **Vehicle Health Monitoring (ELM327 & CAN Protocol)**  
- Used **ELM327 OBD-II scanner** to retrieve vehicle diagnostics:  
  - **Speed, RPM, Fuel Pressure, Engine Oil Temperature**  
- Simulated **ELM327 data** due to lack of car access, helping understand CAN protocol.  
- Integrated **vehicle & driver parameters** for **real-time fleet analytics**.  

### 🔹 **Fleet Management & Real-Time Analysis**  
- **Live tracking & analytics** (location, alerts, driving behavior).  
- **Weekly & Monthly Reports** on driver performance & vehicle health.  
- **WebSocket communication** for seamless real-time data updates.  

## Challenges Faced & Solutions  
| Challenge | Solution |
|-----------|----------|
| **Limited car access for ELM327 testing** | Built a **simulator** to test OBD-II data flow. |
| **Optimizing battery usage in the Flutter app** | Implemented **background processing** for efficient data collection. |
| **Ensuring accurate distraction detection** | Combined **multiple vision-based parameters** for higher precision. |
| **Real-time alert system without user annoyance** | Used **cool emojis & subtle audio alerts** to improve UX. |

## 📈 Impact  
 **Enhanced driver safety** with AI-driven alerts.  
 **Improved vehicle performance monitoring** using real-time analytics.  
 **Fleet-wide optimization** for data-driven decision-making.  

---

**This project represents a fusion of AI, embedded systems, and real-time analytics to improve fleet safety and efficiency.**  
**For collaboration or inquiries, feel free to connect!**  
