🚑 Emergency Ambulance Alert System for Intelligent Traffic Clearance

 📌 Overview

The Emergency Ambulance Alert System is a smart healthcare and traffic management solution that helps ambulances reach hospitals faster by providing real-time GPS tracking, route optimization, and intelligent traffic clearance.

The system continuously tracks the ambulance's live location using GPS, stores the data in Firebase Realtime Database, calculates the optimal route using Flask and the OSRM Routing API, and displays the live movement on an interactive web dashboard.

This project aims to reduce emergency response time and improve coordination between ambulance drivers, hospitals, and traffic authorities.

---
 🚀 Features

- Real-time GPS tracking of ambulances
- Live location synchronization using Firebase Realtime Database
- Dynamic route optimization
- Interactive web dashboard
- Hospital destination selection
- Estimated Time of Arrival (ETA)
- Intelligent traffic signal identification
- Android application for ambulance tracking
- Scalable client-server architecture
- Smart city emergency response solution

---

## 🛠 Tech Stack

### Frontend
- HTML5
- CSS3
- JavaScript
- Leaflet.js

### Backend
- Python
- Flask
- Flask-CORS

### Mobile
- Android
- Kotlin
- Google Location Services

### Database
- Firebase Realtime Database

### APIs
- OSRM Routing API
- Firebase SDK

### Tools
- Visual Studio Code
- Android Studio
- Git
- GitHub

---

# System Architecture

```
Android GPS Device
        │
        ▼
Firebase Realtime Database
        │
        ▼
Python Flask Backend
        │
        ▼
OSRM Route Optimization
        │
        ▼
Web Dashboard
        │
        ▼
Hospital & Traffic Monitoring
```

---

# Modules

### GPS Tracking Module

Continuously tracks ambulance location using Android GPS.

### Route Optimization Module

Calculates the shortest route using the OSRM API.

### Firebase Module

Stores and synchronizes live location data.

### Web Dashboard

Displays live ambulance movement and optimized route.

### Traffic Clearance Module

Identifies nearby traffic signals to create a green corridor.

### Hospital Module

Displays destination hospital information and ETA.

---

# Folder Structure

```
Emergency-Ambulance-Alert-System/

│── backend/
│      app.py
│
│── frontend/
│      index.html
│      script.js
│      styles.css
│
│── android/
│      MainActivity.kt
│
│── documentation/
│      Final_Report.pdf
│
│── screenshots/
│
│── requirements.txt
│── README.md
│── LICENSE
```

---

# Installation

## Clone Repository

```bash
git clone https://github.com/yourusername/Emergency-Ambulance-Alert-System.git
```

Move into project

```bash
cd Emergency-Ambulance-Alert-System
```

Install dependencies

```bash
pip install -r requirements.txt
```

Run Flask Server

```bash
python app.py
```

Open

```
index.html
```

in your browser.

---

# Screenshots

Add screenshots of

- Android Application
- Web Dashboard
- Live Map
- Route Display
- Firebase Database

inside the screenshots folder.

---

# Future Enhancements

- AI-based traffic prediction
- Automatic traffic signal control
- Voice alert system
- Hospital notification system
- Google Maps Traffic API integration
- Multi-ambulance management
- IoT-enabled smart traffic lights

---

# Learning Outcomes

- Flask API Development
- Firebase Integration
- Android GPS Tracking
- Route Optimization
- REST APIs
- Leaflet Maps
- Real-time Data Synchronization
- Smart Transportation Systems

---

# Authors

Neha Pinnamreddy

Bachelor of Technology (Information Technology)

Marri Laxman Reddy Institute of Technology and Management

---

# License

This project is licensed under the MIT License.

---

## ⭐ If you like this project, give it a Star.
