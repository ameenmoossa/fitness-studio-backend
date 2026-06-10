# Fitness Studio Backend

A comprehensive fitness studio management platform backend designed to streamline class scheduling, membership management, attendance tracking, payment processing, user management, and overall studio operations through secure and scalable REST APIs.

The system serves as the core backend infrastructure for the Fitness Studio Management Platform, enabling seamless interaction between members, trainers, and administrators. It supports class bookings, membership subscriptions, attendance monitoring, payment management, scheduling, and operational analytics while ensuring secure and efficient data management.

**Fitness Management • Membership Management • Class Booking • Attendance Tracking • Node.js • Express.js • MongoDB**

---

## 🌟 Features

### User Management

* User registration and authentication
* Member profile management
* Trainer management
* Role-based access control
* Account management

### Membership Management

* Membership plan creation
* Membership subscriptions
* Membership renewal tracking
* Membership status management
* Member lifecycle management

### Class Booking Management

* Class scheduling
* Session booking APIs
* Booking cancellation support
* Booking history management
* Capacity management

### Attendance Tracking

* Member attendance monitoring
* Attendance records management
* Class participation tracking
* Attendance reporting

### Payment Management

* Membership payment processing
* Payment history management
* Billing records
* Revenue tracking
* Transaction monitoring

### Studio Operations

* Schedule management
* Trainer assignment
* Studio activity management
* Operational monitoring

### Analytics & Reporting

* Membership analytics
* Attendance reports
* Revenue statistics
* Studio performance insights

### Authentication & Security

* JWT Authentication
* Password Encryption
* Protected Routes
* Role-Based Access Control

---

## 🏗️ System Architecture

```text
Fitness-Studio-Backend/
│
├── src/
│   ├── controllers/
│   ├── models/
│   ├── routes/
│   ├── middleware/
│   ├── services/
│   ├── utils/
│   └── server.js
│
├── uploads/
├── .env
├── package.json
└── package-lock.json
```

---

## 📋 Prerequisites

* Node.js 18+
* MongoDB
* npm

---

## 🚀 Installation

### 1. Clone Repository

```bash
git clone <repository-url>
cd Fitness-Studio-Backend
```

### 2. Install Dependencies

```bash
npm install
```

### 3. Configure Environment Variables

```env
PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key
```

### 4. Run Development Server

```bash
npm run dev
```

### 5. Run Production Server

```bash
npm start
```

Server runs on:

```text
http://localhost:5000
```

---

## 🎯 API Modules

### Authentication

Handles user registration, login, authorization, and access control.

### Membership Management

Manages membership plans, subscriptions, renewals, and member information.

### Class Booking Management

Handles class schedules, bookings, cancellations, and session tracking.

### Attendance Management

Tracks attendance records and member participation history.

### Payment Management

Processes payments, billing records, and transaction history.

### Trainer Management

Manages trainer profiles, schedules, and assigned sessions.

### Analytics Management

Provides operational insights, attendance reports, and membership statistics.

---

## 📊 Database Collections

| Collection  | Description                        |
| ----------- | ---------------------------------- |
| Users       | Authentication and user accounts   |
| Members     | Member information                 |
| Trainers    | Trainer records                    |
| Memberships | Membership plans and subscriptions |
| Classes     | Fitness classes                    |
| Bookings    | Class booking records              |
| Attendance  | Attendance logs                    |
| Payments    | Payment transactions               |
| Schedules   | Studio schedules                   |

---

## 🔐 User Roles

### Admin

Complete access to memberships, schedules, payments, attendance, analytics, trainers, and studio operations.

### Trainer

Access to assigned classes, schedules, attendance records, and member information.

### Member

Access to bookings, memberships, attendance history, payment records, and personal profile information.

---

## 🛠️ Technologies Used

### Backend

* Node.js
* Express.js

### Database

* MongoDB
* Mongoose

### Authentication

* JWT
* bcryptjs

### File Handling

* Multer

### API Development

* RESTful APIs
* Middleware Architecture

---

## 🔮 Future Enhancements

* Mobile API Support
* AI Fitness Recommendations
* Online Payment Gateway Integration
* Push Notifications
* Wearable Device Integration
* Advanced Revenue Analytics
* Trainer Performance Insights
* Real-Time Class Updates

---

## 📝 Repository Description

Fitness Studio Backend – Node.js and Express.js backend API for managing memberships, class bookings, attendance tracking, schedules, payments, trainers, and fitness studio operations.

---

