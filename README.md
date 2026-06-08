# 🌍 Earthquake Detection and Monitoring System


A real-time Earthquake Detection and Monitoring System designed to detect seismic activities, monitor earthquake events, and provide instant alerts to users. The system utilizes IoT sensors, GPS technology, cloud-based data processing, and a web dashboard to visualize earthquake information and improve disaster preparedness.



---



## 📖 Project Overview


The Earthquake Detection and Monitoring System is an IoT-based solution that continuously monitors ground vibrations using seismic sensors. When abnormal seismic activity is detected, the system analyzes the data, determines the earthquake intensity, and sends real-time alerts to authorities and registered users.

The platform provides:

- Real-time earthquake detection
- Live monitoring dashboard
- Earthquake location tracking
- Alert and notification system
- Historical earthquake data analysis
- Cloud-based data storage

---

## 🎯 Objectives

- Detect seismic activities in real-time.
- Monitor earthquake events continuously.
- Provide early warning alerts.
- Visualize earthquake data on interactive maps.
- Store and analyze historical seismic records.
- Improve disaster preparedness and response.

---

## 🚀 Features

### 🌐 Web Dashboard
- Real-time earthquake monitoring
- Interactive seismic activity map
- Earthquake statistics and analytics
- Historical earthquake records

### 📡 IoT Sensor Integration
- Accelerometer-based vibration detection
- Continuous seismic data collection
- Sensor status monitoring

### 📍 GPS Tracking
- Earthquake epicenter location tracking
- Geographical visualization using maps

### 🚨 Alert System
- SMS notifications
- Email notifications
- Emergency alerts
- Real-time warning messages

### 📊 Data Analytics
- Magnitude analysis
- Seismic trend analysis
- Historical event reports

### 🔐 User Management
- User registration and login
- Role-based access control
- Admin dashboard

---

## 🏗️ System Architecture

```
Seismic Sensor (MPU6050/ADXL345)
            │
            ▼
        ESP32 Device
            │
            ▼
      Cloud Server
            │
    ┌───────┴────────┐
    ▼                ▼
Database       Alert System
    │                │
    ▼                ▼
Web Dashboard   SMS/Email Alerts
```

---

## 🛠️ Technology Stack

### Frontend
- HTML5
- CSS3
- JavaScript
- Bootstrap
- Chart.js
- Leaflet.js

### Backend
- FastAPI / Django
- Python

### Database
- MySQL
- PostgreSQL

### IoT Hardware
- ESP32
- MPU6050 Accelerometer
- ADXL345 Sensor
- GPS Module

### Cloud Platform
- AWS EC2
- AWS RDS
- AWS S3

---

## 📂 Project Structure

```
Earthquake-Detection-System/
│
├── frontend/
│   ├── index.html
│   ├── css/
│   └── js/
│
├── backend/
│   ├── app.py
│   ├── routes/
│   └── models/
│
├── database/
│   └── schema.sql
│
├── iot/
│   ├── esp32_code/
│   └── sensor_data/
│
├── docs/
│   └── project_report/
│
└── README.md
```

---

## ⚙️ Installation

### Clone Repository

```bash
git clone https://github.com/yourusername/Earthquake-Detection-and-Monitoring-System.git
```

### Navigate to Project

```bash
cd Earthquake-Detection-and-Monitoring-System
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

### Run Backend Server

```bash
uvicorn app:app --reload
```

### Open Browser

```text
http://localhost:8000
```

---

## 📊 Future Enhancements

- Machine Learning-based earthquake prediction
- Mobile Application (Android/iOS)
- Integration with National Seismic Networks
- AI-powered anomaly detection
- Real-time satellite data integration
- Voice-based emergency alerts

---

## 👨‍💻 Contributors

- Asha Giri


---

## 📄 License

This project is licensed under the MIT License.

---

## 🙏 Acknowledgements

- USGS Earthquake Data
- OpenStreetMap
- FastAPI Community
- IoT Open Source Community

---

### ⭐ If you find this project useful, don't forget to star the repository!
