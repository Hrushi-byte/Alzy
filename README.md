# Alzy - Alzheimer's Healthcare Android Application

## Overview
Alzy is an advanced Android mobile application designed to assist patients and healthcare professionals in the early detection and management of Alzheimer's disease. It offers a comprehensive platform featuring symptom tracking, appointment management, medication reminders, AI-powered MRI scan analysis, cognitive games, educational content, and secure patient-doctor communication.

## Features
- **User Authentication:** Secure signup and login with role-based dashboards for patients and doctors.
- **Symptom Tracking:** Patients can log symptoms and track their progression over time.
- **Appointment Scheduling:** Book, view, and manage doctor appointments in an integrated calendar.
- **Medication Management:** Schedule medication intake with reminders and logs.
- **Medical Records & Imaging:** Upload, view, and manage medical records, including MRI scans with AI-driven analysis via TensorFlow Lite.
- **Cognitive Games:** Suite of brain health games to stimulate cognitive function and track performance.
- **Health Education:** Access to nutrition tips, sleep hygiene, meditation, and other wellness content.
- **Communication:** Real-time chat between patients and doctors, plus AI chatbot powered by Gemini API for support.
- **Community Support:** Peer forums and customer support channels integrated within the app.
- **Notifications:** Real-time reminders and alerts for medications, appointments, and important messages.

## Tech Stack
- **Language:** Java
- **IDE:** Android Studio
- **Backend:** Firebase Authentication, Realtime Database, and Cloud Storage
- **Machine Learning:** TensorFlow Lite for on-device Alzheimer’s detection from MRI scans
- **Image Loading:** Glide library for efficient image handling
- **Networking:** Retrofit (optional for API requests)
- **Other:** Gemini API for AI chatbot support, SQLite for offline data caching

## Architecture
- Modular design with separate packages for activities, adapters, models, and utilities
- Use of RecyclerView adapters for dynamic content lists (e.g., medical records, messages)
- Role-based navigation with custom dashboards for patients and doctors
- Integration of AI model for MRI inference results displayed within the app
- Firebase backend integration for secure and real-time data sync

## Setup and Installation
1. Clone the repository:
