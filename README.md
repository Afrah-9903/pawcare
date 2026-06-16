  🐾 PawCare

## Animal Care & Welfare Management Platform

### Date

June 2026

### Author

#### Afrah Mohammed [Instagram](https://www.instagram.com/_afrah_mohammed/)| [GitHub](https://github.com/Afrah) | [LinkedIn](<[www.linkedin.com/in/aboodisa](https://www.linkedin.com/in/afrah-mohd-6ab257276/)>)

---

# 📖 Project Overview

PawCare is a full-stack Animal Care & Welfare Management Platform designed to help municipalities, NGOs, veterinarians, animal shelters, and volunteers manage animal welfare operations from a single dashboard.

The system centralizes animal registration, vaccination tracking, sterilization programs, resident complaints, rescue requests, shelter capacity monitoring, volunteer activities, and task management.

The goal is to improve transparency, coordination, and efficiency in animal welfare programs.

---

# 🎯 Problem Statement

Animal welfare organizations often rely on spreadsheets, paper records, and disconnected systems to manage animal care activities.

PawCare provides a centralized platform where organizations can:

* Track animal welfare records
* Monitor vaccination campaigns
* Manage sterilization programs
* Handle resident complaints
* Coordinate rescue operations
* Monitor shelter capacity
* Track volunteer activities

---

# 🚀 MVP Features

## 🔐 Authentication

* User Registration
* User Login
* User Logout
* Protected Routes
* Role-Based Access Control

### Roles

* Admin
* Municipality Staff
* Veterinarian
* Volunteer
* NGO Staff

---

## 🐕 Animal Registry

* Register Animal
* Edit Animal Records
* Upload Animal Photos
* Track Animal Status
* Search Animals
* Filter Animals

### Animal Status

* Vaccinated
* Sterilized
* Under Observation
* In Shelter
* Released
* Deceased

---

## 💉 Vaccination Management

* Record Vaccinations
* Vaccination History
* Vaccination Reports
* Due Vaccination Tracking

---

## 🏥 Sterilization Tracking

* Record Sterilization Procedures
* Procedure History
* Program Monitoring

---

## 📢 Resident Complaints

Residents can report:

* Injured Animals
* Aggressive Animals
* Animal Abuse
* Dead Animals
* Stray Animal Concerns

### Complaint Features

* Create Complaint
* Upload Evidence Photos
* Track Status
* Assign Teams
* Resolution Tracking

---

## 🚑 Rescue & Pickup Requests

* Create Pickup Requests
* Assign Volunteers
* Assign Rescue Teams
* Track Progress
* Update Status

---

## 🏠 Shelter Management

### Shelter Dashboard

* Total Capacity
* Current Occupancy
* Available Spaces
* Animal Distribution

---

## 🤝 Volunteer Dashboard

### Volunteer Features

* Assigned Tasks
* Completed Tasks
* Active Requests
* Activity Tracking

---

## 📊 Admin Dashboard

### Analytics

* Animals Registered
* Vaccination Statistics
* Sterilization Statistics
* Open Complaints
* Active Rescue Requests
* Shelter Occupancy
* Volunteer Performance

---

# 🖥️ Wireframes

## Login Page

 <img width="1536" height="1024" alt="Login" src="https://github.com/user-attachments/assets/8669f132-2bd8-49fa-8df8-486cac90c38b" />


## Dashboard

 <img width="1536" height="1024" alt="DashBoard" src="https://github.com/user-attachments/assets/48ba2cff-9b9d-4b72-b54f-25d68f6a8424" />


## Animal Registry

 <img width="1536" height="1024" alt="Animal Registry " src="https://github.com/user-attachments/assets/c4cde482-1d5b-40ec-99bc-718d96b4c402" />


## Animal Profile

 <img width="1536" height="1024" alt="Animal Profile" src="https://github.com/user-attachments/assets/b1b03d59-ce6e-4fc4-a439-52508892106c" />


## Resident Complaints

 <img width="1536" height="1024" alt="Resident Complaints" src="https://github.com/user-attachments/assets/49377211-e37a-4bc8-89d4-97165f64c949" />


## Rescue Requests

 <img width="1536" height="1024" alt="Rescue Requests " src="https://github.com/user-attachments/assets/a1c65a3c-924e-468d-a270-cdd56380e1fa" />


## Volunteer Dashboard

 <img width="1536" height="1024" alt="Volunteer Dashboard" src="https://github.com/user-attachments/assets/14346acd-91c9-4935-b0ff-4c2f4d3df18f" />


## Shelter Dashboard

 <img width="1536" height="1024" alt=" Shelter Dashboard" src="https://github.com/user-attachments/assets/1a8af77a-ee8e-4c31-b22b-f4159662fbf0" />


## Admin Dashboard

 <img width="1536" height="1024" alt="Admin Dashboard" src="https://github.com/user-attachments/assets/8953b2a9-71a9-49ea-a4ed-7dd310696aad" />


---

# 🗺️ ERD Diagram

 <img width="1536" height="1024" alt="PaWCareERD" src="https://github.com/user-attachments/assets/0edad3e1-d94c-47e1-901d-5f207ef20886" />


---

# 🗄️ Database Tables

### profiles

Stores system users and roles.

### animals

Stores animal records.

### vaccinations

Stores vaccination history.

### sterilizations

Stores sterilization records.

### resident_complaints

Stores resident complaints.

### pickup_requests

Stores rescue requests.

### shelters

Stores shelter information.

### volunteers

Stores volunteer records.

### tasks

Stores assigned activities.

### task_updates

Stores task progress updates.

---

# 🛠️ Technologies Used

## Frontend

* React
* React Router
* CSS

## Backend Services

* Supabase Auth
* Supabase PostgreSQL
* Supabase Storage

## Deployment

* Vercel

---

# 📂 Planned Folder Structure

```bash
src/
│
├── components/
├── pages/
├── services/
├── hooks/
├── assets/
│
├── App.jsx
└── main.jsx
```

---

# 🎓 Learning Objectives

This project is being built to practice:

* React Fundamentals
* React Router
* Authentication
* PostgreSQL Database Design
* CRUD Operations
* Role-Based Access Control
* Dashboard Development
* File Uploads
* Full Stack Application Architecture
* Deployment

---

# 🔮 Future Enhancements

## Phase 2 – Smart Operations

### 🗺️ Interactive Maps

* View animal locations on a live map
* Display complaint hotspots
* Track rescue request locations
* Visualize shelter locations

### 📍 Animal Location Tracking

* Last known animal location
* Rescue history timeline
* Area-based animal monitoring
* Animal movement records

### 📧 Email Notifications

* Complaint status updates
* Rescue assignment notifications
* Vaccination reminders
* Shelter capacity alerts

### 📱 SMS Notifications

* Rescue team alerts
* Emergency complaint notifications
* Vaccination reminders
* Volunteer task assignments

---

## Phase 3 – Advanced Features

### 📲 Mobile Application

* Volunteer mobile app
* Resident complaint submission
* Rescue team mobile dashboard
* Real-time updates in the field

### 🏷️ QR Code Animal Identification

* Unique QR code for every animal
* Scan to view animal history
* Vaccination records
* Sterilization records
* Rescue and treatment history

### 🤖 AI Analytics

* Complaint trend analysis
* High-risk area prediction
* Shelter occupancy forecasting
* Vaccination campaign insights
* Volunteer performance analytics

### 🌍 Multi-City Support

* Support multiple municipalities
* City-level dashboards
* Regional reporting
* Cross-city statistics
* Centralized administration

---

## Phase 4 – Enterprise Features

### 📊 Advanced Reporting

* Monthly welfare reports
* Vaccination campaign reports
* Rescue operation reports
* Volunteer contribution reports

### 🏥 Veterinary Management

* Treatment records
* Medical history tracking
* Surgery records
* Follow-up schedules

### 💰 Donation Management

* Online donations
* Sponsorship programs
* Campaign fundraising
* Financial reporting

### 🔗 Government Integration

* Municipality portals
* Public reporting dashboards
* Open data exports
* Welfare compliance tracking


### Progress
 <a href = "https://trello.com/b/wLGJGinO/pawcare"> Trello </a>

 

 
