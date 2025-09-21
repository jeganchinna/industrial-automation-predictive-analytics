# industrial-automation-predictive-analytics
This case study presents the development of a cloud-based predictive maintenance pipeline for industrial automation.
# Industrial Automation Predictive Analytics Case Study

## 📌 Introduction
This project demonstrates the development of a **cloud-based predictive maintenance pipeline** for industrial automation.  
It integrates **data simulation, cleaning, preprocessing, machine learning prediction, and visualization with alerting**.

## 🎯 Objectives
- Simulate real-time machine sensor data (vibration, temperature, motor load).  
- Store and manage time-series data in **InfluxDB Cloud**.  
- Visualize live machine operations in **Grafana Cloud**.  
- Train and integrate a **machine learning model** for failure prediction.  
- Create **alert rules** to notify stakeholders of predicted failures.  

## 🏗️ System Architecture
The system consists of:  
- **Google Colab** → Data simulation, cleaning, preprocessing, ML training.  
- **InfluxDB Cloud** → Storage of sensor and prediction data.  
- **Grafana Cloud** → Dashboards and alerts.  

![Architecture Diagram](Industrial_Automation_Architecture.png)

## 📂 Project Structure
├── Industrial_Automation_Case_Study_With_Diagram.docx # Full case study report
├── sample_data1.csv # Sample machine dataset
├── colab_notebook.ipynb # Data cleaning, ML, streaming code
├── Industrial_Automation_Architecture.png # Architecture flow diagram
├── README.md # Project overview

## ⚙️ Implementation Steps
1. Upload and clean dataset in Google Colab.  
2. Train ML model (RandomForestClassifier).  
3. Stream cleaned + predicted data to InfluxDB Cloud.  
4. Query and visualize in Grafana Cloud dashboards.  
5. Add prediction panel + alerts.  

## 📊 Results
- **Dashboard panels** show vibration, temperature, motor load, actual failures, and **predicted failures**.  
- Alerts notify via email when `predicted_failure = 1`.  

## 🚀 Future Scope
- Scale to multiple machines.  
- Use advanced ML/DL (LSTM, anomaly detection).  
- Edge AI deployment for real-time decision-making.  

---

👨‍💻 **Author**: Jeganathan C  
📅 **Year**: 2025  
