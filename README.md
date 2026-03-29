# 🚗 ParkSmart AI – Intelligent Parking System

## 📌 Overview

**EIRA** is a smart parking management system that uses **AI, cameras, and radar sensors** to detect vehicles and manage parking slots in real-time.

The system automatically identifies vehicle entry, checks slot availability, assigns the nearest parking space, and updates the status without manual intervention.

---

## ⚙️ Features

* 🚗 Real-time vehicle detection using **camera + radar sensors**
* 🅿️ Live parking slot availability (Available / Occupied)
* 📍 Automatic slot allocation
* 🧭 Navigation guidance to parking slot
* 🔄 Real-time status updates
* 🔔 Notifications for parking events

---

## 🏗️ Workflow Architecture

### 1. Trigger

* System starts when a **vehicle enters the parking area**

### 2. Detection

* Camera + radar sensors detect vehicle presence

### 3. Processing

* AI processes input and identifies slot availability

### 4. Decision Logic

* If slot available → assign nearest slot
* If full → notify user

### 5. Actions

* Update parking database
* Display slot status on dashboard
* Send notifications to user

---

## 🔄 Workflow Logic (Simplified)

Vehicle Entry → Detect Vehicle → Check Slots →
→ Assign Slot → Update System → Navigate User → Park → Exit → Update Slot

---

## 🧰 Tech Stack

* AI / Machine Learning
* Camera & Radar Sensors
* Workflow Automation (Logic Flow)
* Database (Google Sheets / Cloud)
* Frontend UI (Dashboard App)

---



---

## 📜 License

This project is developed for educational purposes.
