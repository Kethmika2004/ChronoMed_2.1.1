# 🏥 ChronoMed v2.1

> A modern, secure, and concurrent safe hospital queue management system that simplifies appointment booking and enables real time queue management for both patients and doctors.

<p align="center">
  <img width="1920" height="1080" alt="hero-medical" src="https://github.com/user-attachments/assets/cbae042c-dbde-4f3a-af5c-fd0df4d34ad5" />
</p>

---

## 📖 Overview

Long waiting times and inefficient queue management are common challenges in healthcare systems. **ChronoMed v2.1** addresses these issues by providing a secure, real time platform where patients can book appointments while doctors efficiently manage their consultation queues.

The system focuses on **performance, security, concurrency, and user experience**, making the appointment process smooth for both patients and healthcare providers now expanding into a full **mobile app with AI powered features**.

---

## ✨ Current Features

### 👤 Authentication & Security
- JWT Authentication
- Role Based Access Control
- Patient Registration
- Secure Password Encryption
- Protected REST APIs

### 🩺 Patient Portal
- Patient Registration & Login
- Search Doctors
- Filter by Specialization
- Book Appointments
- Receive Instant Queue Number
- View Live Queue Status

### 👨‍⚕️ Doctor Dashboard
- Secure Doctor Login
- Live Queue Dashboard
- Call Next Patient
- Start Consultation
- Complete Consultation
- Queue Statistics

### ⚡ Queue Management
- Concurrent safe appointment booking
- Thread safe queue allocation
- Live queue synchronization
- Prevent duplicate queue numbers
- Automatic appointment status updates

---

## 🛠 Tech Stack

### Frontend
- React.js (Vite)
- Tailwind CSS v4
- React Router
- Axios
- Lucide React
- Capacitor (Android mobile app)

### Backend
- Java 17
- Spring Boot 3
- Spring Security
- Spring Data JPA
- Hibernate

### Database
- PostgreSQL (Supabase)

### Authentication
- JWT (JSON Web Tokens)

---

## 📸 Preview

### Login & Authentication

<p align="center">
<img width="2560" height="1600" alt="Login screen" src="https://github.com/user-attachments/assets/501755fa-9870-4f61-b76a-893d86cf24f1" />
</p>

Secure role-based authentication for Patients and Doctors using JWT.

---

### Patient Portal

<p align="center">
<img width="2560" height="1600" alt="Patient portal" src="https://github.com/user-attachments/assets/5e938734-034e-4d7d-b175-8571d6207923" />
</p>

Patients can book a channeling appointment and track the queue in real time.

---

### Doctor Dashboard

<p align="center">
<img width="1600" height="1000" alt="Doctor dashboard" src="https://github.com/user-attachments/assets/3dcabe13-a5f6-4802-b80c-33c86db96022" />
</p>

Doctors can monitor queues, call the next patient, and manage consultations in real time.

---

### Admin (Hospital) Dashboard

<p align="center">
<img width="1600" height="1000" alt="Admin dashboard" src="https://github.com/user-attachments/assets/7d589440-159c-469e-90f3-ac7aa3b53136" />
</p>

Hospitals can manage consultations in real time and see the queue and available doctors at any given moment.

---

## 🔐 Security Highlights

- JWT Authentication
- Password Encryption
- Protected REST Endpoints
- Role-based Authorization
- Secure API Communication

---

## ⚙️ Concurrency

ChronoMed implements a **thread-safe booking mechanism** to ensure:

- No duplicate queue numbers
- Consistent appointment ordering
- Reliable booking under concurrent requests

---

## 🚀 Roadmap - v2.1 Upgrades In Progress

ChronoMed is evolving into a fully featured mobile hospital platform with real time alerts and AI assisted care. Below is the complete build roadmap, grouped by priority.

### 🚨 Foundation (Blockers)
1. **Android ↔ Backend Connectivity Fix** - proper LAN/production networking, CORS whitelist, verified on physical device
2. **In App Health Check** - live connected/disconnected status indicator

### 🔔 Flagship Feature
3. **"You're Up Now" Alarm Alert** - full-screen, loud, looping alert the moment it's the patient's turn, with SMS fallback if the app is closed

### 🤖 AI / ML Features
4. **AI Symptom Triage at Booking** - suggests urgency level and routes to the right specialty
5. **AI Prescription Reader** - photograph a handwritten prescription and get a clean, typed transcription, with a "verify with your pharmacist" flag on low-confidence reads
6. **AI Medical Report Summarizer** - explains lab report values in plain language
7. **AI Disease Pattern Flagging** *(roadmap tier)* - highlights patterns worth discussing with a doctor; not a diagnosis
8. **Wait Time Prediction** - estimated wait per patient using historical queue data
9. **AI Generated Doctor Visit Summaries** - turns short doctor notes into structured visit records
10. **Queue Re-Prioritization Algorithm** - scores urgency, wait time, and no-show risk to optimize ordering

### 👤 Patient-Facing Features
11. **Patient History Upload** -  past symptoms, prescriptions, and lab reports (PDFs/images) tied to the patient's account
12. **Standard Push Notifications** - "you're 3rd in line" style live updates
13. **Video Consultation** - integrated telehealth calls
14. **Appointment Reminders** - SMS/email
15. **Multi Language Toggle** - Sinhala / English

### 🩺 Doctor & Admin Features
16. **Patient History View** - doctors see uploaded reports and past visits before the consultation
17. **Analytics Dashboard** - patients per day, average wait time, peak hours
18. **Admin Panel** - manage doctors, schedules, and role-based access

### 💳 Nice-to-Have
19. **Payments** - online payment gateway integration
20. **HTTPS / Certificate Setup** - required for demoing and deploying beyond a local network

Stay tuned ! more exciting features are on the way!

---

## 👨‍💻 Team MultiThreaders

- Yasandu Kethmika
- Nimsara Kodithuwakku
- Kenul Perera
- Risandu Dissanayake
- Chamitha Botheju

---

## 🙏 Acknowledgements

A heartfelt thank you to **Prof. Chandana Gamage** for providing us with the opportunity, guidance, and encouragement throughout the development of this project.

---

⭐ If you like this project, don't forget to give the repository a star!
