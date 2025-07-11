# USB Device Usage Prediction System 🔐

This project uses **Splunk’s Machine Learning Toolkit** to predict USB data write usage (`write_kb`) and detect anomalies in USB behavior based on synthetic log data.

## 🚀 Project Objective
To monitor USB activity and flag unusual write patterns that may indicate suspicious behavior.

## 🔧 Built With
- Splunk Enterprise 9.x
- Splunk Machine Learning Toolkit
- Python (Random Forest model within Splunk)
- SPL (Search Processing Language)
- Dashboard Studio

## 📊 Features
- Trained a Random Forest model to predict `write_kb`
- Visual dashboard showing actual vs predicted data
- Bar chart comparing usage

## 📁 Folder Overview
- `data/`: Synthetic USB log data used for training
- `model/`: Description of trained Random Forest model
- `dashboard_screenshots/`: Dashboard and chart screenshots
- `spl_query.txt`: All SPL queries used

## 📷 Dashboard Preview
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/ca46e30a-b901-4b6a-abfb-26f5329f5b89" />

