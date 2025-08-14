# SwiftParcel Manager

A parcel booking and delivery management platform built with **Spring Boot (Java)** for the backend and a modern frontend interface.  
Supports role-based workflows for customers, couriers, and administrators, along with real-time parcel tracking.

## 🚀 Features
- Book parcels with detailed sender/receiver info
- Role-based dashboards: Customer, Courier, Admin
- Parcel status tracking and history
- Event-driven updates with Kafka (future-ready)
- REST API for parcel data

## 🛠 Tech Stack
- Backend: Java 17, Spring Boot, REST API
- Frontend: React + JavaScript
- Database: MySQL (prod) / H2 (dev)
- Version Control: Git + GitHub

## 📂 Structure
- `/backend` – Spring Boot application
- `/frontend` – React app

## 🧑‍💻 Setup
```bash
# Backend
mvn spring-boot:run
# Frontend
npm install && npm start
