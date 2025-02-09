# 🌡️ IoT-Enabled HVAC Fault Detection System

## 📋 Project Overview
This project focuses on developing an **IoT-enabled Machine Learning (ML) solution** for **fault detection and diagnosis** in **HVAC (Heating, Ventilation, and Air Conditioning) systems**. The goal is to enhance **energy efficiency**, reduce maintenance costs, and improve system reliability through real-time data monitoring and predictive analytics.

The system leverages **live sensor data**, which is processed through the **ST AIOT platform** and integrated with ML models to detect anomalies and predict potential faults. The solution aims to support proactive maintenance, reduce operational costs, and improve indoor air quality.

---

## 🚀 Key Features
- **Real-Time Data Monitoring:** Collects data from various HVAC components using IoT sensors.  
- **Anomaly Detection:** Implements ML models with **over 95% accuracy** to detect system anomalies.  
- **Predictive Maintenance:** Identifies potential issues before they escalate, reducing hardware damage risks by **3×**.  
- **Energy Optimization:** Helps improve HVAC energy efficiency by detecting inefficiencies early.  
- **Scalable Architecture:** Designed to be scalable for commercial buildings, data centers, and healthcare facilities.  

---

## 🔍 Problem Statement
Traditional HVAC systems rely on reactive maintenance, leading to increased energy consumption, unexpected breakdowns, and higher maintenance costs. This project addresses these challenges by enabling **predictive fault detection** through IoT and ML technologies.

---

## 🏗️ DATA COLLECTION METHODS
<img width="787" alt="Screenshot 2025-02-09 at 4 04 17 PM" src="https://github.com/user-attachments/assets/0ae243a0-5f1d-4a3d-a035-0fcbf3a236c8" />

### **Components Used:**
- **STM SensorTile Box:** For collecting real-time data.  
- **IoT Sensors:** Temperature, humidity, pressure, gas, vibration, current, and voltage sensors.  
- **ST AIOT Platform:** For data processing and model deployment.  
- **Machine Learning Algorithms:** Decision Trees and Anomaly Detection Models.  

---

## 🛠️ Tools & Technologies
- **Hardware:** STM32 Microcontroller, IoT Sensors  
- **Software:**  
  - **ST AIOT Platform** (for IoT data management)  
  - **CubeMX** (for STM board calibration)  
  - **KiCad** (for PCB design)  
  - **Python (scikit-learn)** (for ML model development)  
  - **Cloud Services** (for data storage and remote monitoring)  

---

## 📊 Dataset & Model
- **Dataset:** Time-series dataset from [ASHRAE](https://faultdetection.lbl.gov/data/), containing labeled HVAC operational data.  
- **ML Model:**  
  - **Binary Decision Tree** algorithm for anomaly detection.  
  - Achieved **95%+ accuracy** in detecting HVAC faults.  
  - Model trained to reduce hardware damage risks by **3×** through early detection.  

---

## ⚙️ System Workflow
1. **Data Collection:** IoT sensors gather data on temperature, pressure, humidity, energy consumption, etc.  
2. **Data Processing:** The data is processed through the STM32 board and transmitted to the ST AIOT platform.  
3. **Anomaly Detection:** ML models analyze the data for irregularities, identifying potential faults.  
4. **Fault Diagnosis:** Generates real-time alerts for maintenance teams, preventing system failures.  
5. **Dashboard Visualization:** Key metrics like energy consumption, anomaly reports, and system health are displayed on a centralized dashboard.  


## 📈 Results & Performance
- Achieved **95%+ accuracy** in fault detection.  
- Reduced HVAC hardware damage risk by **3×** through predictive maintenance.  
- Optimized energy efficiency by identifying system inefficiencies early.  



## 🧪 Future Work
- **Pilot Deployment:** Testing on IIIT Delhi's HVAC system to validate model performance in real-world conditions.  
- **Sensor Bias Estimation:** Calibrating model performance based on differences in deployed sensors.  
- **Scalability:** Expanding to commercial setups like data centers, hospitals, and smart buildings.  





