# 🍌 Banana Game

An interactive web-based puzzle game developed using React (Frontend), Java (Backend), and MySQL (Database).  
This project was created to fulfill university requirements while focusing on user experience, clean architecture, and smooth gameplay.

---

## 🚀 Tech Stack

### 🎨 Frontend
- ⚛️ React.js
- 🎨 CSS3
- 📜 JavaScript

### ⚙️ Backend
- ☕ Java (OOP Principles)
- 🔄 Express.js (API handling)

### 🗄️ Database
- 🐬 MySQL

---

## 🎮 Features

- ✨ Interactive and dynamic UI
- 🎨 Themed design with glowing effects and animations
- 📊 Real-time progress tracking
- 🏆 Leaderboard system
- 👤 User authentication
- 🆔 UUID-based unique player identity
- ⚡ Event-driven client-server communication
- 🎯 Smooth and accessible gameplay for all ages

---

## 🖥️ Frontend Overview

The frontend is built using **React** to create reusable and dynamic components.  
The interface is designed to be:

- Clean and engaging  
- Responsive and smooth  
- Visually appealing with animations  
- Easy to use for players of all ages  

User interactions trigger events that update the view instantly or communicate with the backend server.

---

## ⚙️ Backend Architecture

The backend follows **Object-Oriented Programming (OOP)** principles for modularity and maintainability.

### 📦 Core Classes

#### 👤 User
- Handles authentication
- Maintains player scores
- Generates and stores UUID for each player

#### 🏆 Leaderboard
- Manages score entries
- Retrieves and updates rankings
- Displays top players

Each player is assigned a **UUID** at registration, stored in the database for unique tracking of progress and scores.

---

## 🔄 Event-Driven Design

### 🖱️ Client-Side
- User actions trigger events
- Events update UI or send API requests

### 🖥️ Server-Side
- Express.js handles incoming requests
- Processes data and sends appropriate responses

This ensures smooth communication between frontend and backend.

---

## 🗄️ Database

MySQL stores:
- 👤 User credentials
- 🆔 UUIDs
- 📊 Player scores
- 🏆 Leaderboard data

---

## 🛠️ Installation

### 1️⃣ Clone Repository
