
# 🏛️ Govt_App — Citizen Grievance Reporting Mobile Application

A smart mobile application that enables citizens to report civic issues directly to municipal authorities using AI-powered complaint generation, voice input, and automatic department routing.

---

## 📌 Project Overview

**Govt_App** is a citizen-centric grievance management system designed to simplify the process of reporting public infrastructure and municipal issues such as:

- Power cuts ⚡
- Drainage problems 💧
- Water supply issues 🚰
- Improper sewage treatment 🚧
- Road damage 🛣️
- Other local civic complaints

The app analyzes user input (text or voice), identifies the issue using AI, and automatically assigns the complaint to the appropriate government department for resolution.

---

## 🎯 Target Users

👥 Citizens only

This application is designed for public use by residents to report issues within their municipality or corporation area.

---

## 🚀 Key Features

### 🔐 Authentication
- Mobile number OTP login
- Mandatory registration for new users
- Personal details stored securely using Firebase

### 📝 Smart Complaint Submission
- AI-assisted text generation
- Voice input with speech-to-text conversion
- Automatic issue detection from user input
- Department identification (e.g., Highway Dept, Rural Dept)

### 📷 Evidence & Location Support
- Photo upload for complaints
- Automatic GPS location detection
- Location used for accurate issue mapping

### 🧠 AI Analysis Engine
- Determines issue category
- Assigns responsible department
- Calculates priority level
- Provides estimated resolution time
- Zone identification

### 📊 Complaint Tracking
- Real-time status updates
- Active / Resolved tracking
- Complaint history access
- Detailed complaint view

### 🏠 Citizen Dashboard
- Filed complaints count
- Active cases
- Resolved cases
- Live civic activity feed

---

## 🛠️ Tech Stack

### 📱 Frontend (Mobile)
- React Native
- Expo

### ☁️ Backend & Database
- Firebase Authentication
- Firebase Realtime Database / Firestore

### 🤖 AI & Voice Processing
- Google Gemini API (for voice analysis and AI processing)

### 📍 Other Features
- GPS location services
- Image upload handling
- OTP verification system

---

## ⚙️ Installation & Setup

### 1️⃣ Clone the repository

```bash
git clone https://github.com/Hari3856/Govt_App.git
