# 🚆 Railway Booking System (Java CLI Backend)

A fully functional advanced **Command-Line Railway Booking System** built entirely with **Java** to simulate backend logic. It demonstrates key software engineering concepts like **Object-Oriented Programming**, **Low-Level Design**, **data persistence with JSON**, and **secure authentication** using jBCrypt — all without any frameworks.

---

## 🛠️ Tech Stack

- **Java CLI**
- **OOP Principles & LLD**
- **Jackson (ObjectMapper)**
- **jBCrypt** (for secure password storage)
- **JSON** for file-based database
- **Streams, Optionals, Predicates** (Functional Java)

---

## 🚀 Features

### 👤 User Management
- Signup and Login with **encrypted passwords**
- Email based unique user identity
- Tracks **ticket history** for each user

### 🚆 Train System
- Store train data including train ID, name, stations list
- **2D matrix seat layout** to simulate real seat booking
- Prevents overbooking and duplicates

### 🎫 Booking & Ticketing
- Book tickets based on source and destination
- Show available trains and seats
- Cancel existing bookings

### 🧰 Utilities
- File-based data persistence using **Jackson ObjectMapper**
- Custom logic with **Streams**, **filter**, **Optional**, **removeIf**
- Exception handling using **IOException**

---

## 📁 Project Structure

RailwayBookingSystem/
│
├── src/
│   └── org/
│       └── example/
│           ├── App.java
│
│           ├── entities/
│           │   ├── User.java
│           │   ├── Train.java
│           │   └── Ticket.java
│
│           ├── services/
│           │   ├── UserBookingService.java
│           │   └── TrainService.java
│
│           └── utils/
│               └── JsonUtil.java              <-- (optional helper for reading/writing JSON)
│
├── localDB/
│   ├── users.json
│   └── trains.json
│
├── lib/
│   ├── jackson-databind.jar                  <-- (or from Maven/Gradle)
│   └── jbcrypt.jar
│
├── README.md
├── .gitignore
└── build.gradle / pom.xml                    <-- If using Gradle or Maven





---

## 📦 Requirements

- Java JDK 17
- IntelliJ IDEA (or any Java IDE)
- jBCrypt library
- Jackson Databind library
