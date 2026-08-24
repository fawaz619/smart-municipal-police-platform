# 🚓 Smart Municipal Police Field Operations Platform

A full-stack municipal police field operations proof-of-concept platform designed to support field officers, dispatchers, and supervisors through connected mobile, web, and backend applications.

## 📌 Project Overview

The platform brings together three main components:

- 📱 **Android Application** — mobile application for field officers
- 🌐 **Web Dashboard** — dispatcher and supervisor interface
- ⚙️ **Backend API** — REST API and database services

The system is designed to support municipal police operations by providing connected tools for field activities, incident management, and operational coordination.

---

## 🎯 Project Objectives

The main objectives of the project are to:

- Provide field officers with a dedicated mobile application
- Support dispatchers and supervisors through a web dashboard
- Connect the mobile and web applications through REST APIs
- Centralize operational data
- Improve communication between field and administrative teams
- Provide a structured foundation for future municipal police services

---

## 📱 Android Application

The Android application is designed for municipal police officers working in the field.

Key areas include:

- Officer authentication
- Mobile field workflows
- Incident and report management
- Access to operational information
- Communication with backend services
- Mobile-friendly user interface

### Android Technologies

- Android Studio
- Java / Kotlin
- XML
- REST API integration
- HTTP/JSON communication

---

## 🌐 Web Dashboard

The web application provides interfaces for dispatchers and supervisors.

It is designed to support:

- Dispatcher workflows
- Supervisor workflows
- Operational monitoring
- Data visualization
- Backend API integration
- User authentication

### Web Technologies

- React
- TypeScript / JavaScript
- HTML
- CSS
- REST API

---

## ⚙️ Backend

The backend provides the services required by the Android and web applications.

Responsibilities include:

- REST API endpoints
- Authentication
- Data management
- Business logic
- Database communication
- Integration between mobile and web components

### Backend Technologies

- Django
- Django REST Framework
- PostgreSQL
- REST APIs
- Python

---

## 🏗️ System Architecture


                    ┌─────────────────────┐
                    │     Web Dashboard   │
                    │ Dispatcher / Admin  │
                    └──────────┬──────────┘
                               │
                               │ REST API
                               ▼
                    ┌─────────────────────┐
                    │       Backend       │
                    │ Django REST API     │
                    └──────────┬──────────┘
                               │
                               │
                 ┌─────────────┴─────────────┐
                 │                           │
                 ▼                           ▼
        ┌─────────────────┐         ┌─────────────────┐
        │ Android Officer │         │    Database     │
        │    Application  │         │   PostgreSQL    │
        └─────────────────┘         └─────────────────┘
| Component       | Technologies                          |
| --------------- | ------------------------------------- |
| Mobile          | Android Studio, Java/Kotlin, XML      |
| Web             | React, TypeScript/JavaScript          |
| Backend         | Python, Django, Django REST Framework |
| Database        | PostgreSQL                            |
| Communication   | REST API, JSON                        |
| Version Control | Git, GitHub                           |




👨‍💻 My Contribution

This project was developed as a team project.

My primary contribution focused on the Android/mobile application.

My responsibilities included:
Android application development using Android Studio
Mobile UI implementation
Implementing application workflows
Integrating the Android application with backend APIs
Testing mobile functionality
Debugging and resolving application issues
Working with the team to integrate the mobile application with the overall system

