<h1 align="center">🏨 Aura Stay</h1>

### A multi-property hotel management and rental platform — Book, host, and manage properties seamlessly


![React](https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=node.js&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white)
![TailwindCSS](https://img.shields.io/badge/TailwindCSS-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white)
![Razorpay](https://img.shields.io/badge/Razorpay-0C4A82?style=for-the-badge&logo=razorpay&logoColor=white)
![Nodemailer](https://img.shields.io/badge/Nodemailer-D14836?style=for-the-badge&logo=postman&logoColor=white)
![Redux](https://img.shields.io/badge/Redux-764ABC?style=for-the-badge&logo=redux&logoColor=white)
![Express](https://img.shields.io/badge/Express-000000?style=for-the-badge&logo=express&logoColor=white)

---

## 🤖 Introduction

Aura Stay is a full-stack multi-property hotel management and rental platform where:

- 🏠 Renters (Hosts) can list and manage properties.
- 🧳 Guests (Users) can browse, book, and pay for properties securely.
- 👑 Admins manage users, properties, bookings, and payments.

Built with React, Node.js, MongoDB, TailwindCSS, and integrated with Razorpay and Nodemailer, it provides a modern, user-friendly experience for property management and online bookings.

---
## Live demo

[🌐 Live Demo](https://hotel-management-frontend-topaz.vercel.app/)

---
## 📸 Screenshots

<h1 align="center"> User Interface</h1>

<p align="center">
  <img src="/images/dashboard.png" width="700">
</p>
<p align="center">
  <img src="/images/bookingPage.png" width="700">
</p>
<p align="center">
  <img src="/images/property.png" width="700">
</p>
<p align="center">
  <img src="/images/reviews.png" width="700">
</p>
<p align="center">
  <img src="/images/myProperties.png" width="700">
</p>
<p align="center">
  <img src="/images/myBookings.png" width="700">
</p>
<p align="center">
  <img src="/images/bookingConfirmation.png" width="700">
</p>
---

<h1 align="center"> Admin Interface</h1>

<p align="center">
  <img src="/images/adminUsers.png" width="700">
</p>
<p align="center">
  <img src="/images/allProperties.png" width="700">
</p>

<p align="center">
  <img src="/images/allBookings.png" width="700">
</p>
<p align="center">
  <img src="/images/allPayments.png" width="700">
</p>


---

## ⚙️ Tech Stack

- ⚛️ React – Frontend UI
- 🟢 Node.js + Express – Backend REST API
- 🍃 MongoDB + Mongoose – Database & data modeling
- 🎨 TailwindCSS – Styling and responsive design
- 💳 Razorpay – Payment processing
- 📧 Nodemailer – Email notifications
- 🔑 JWT + bcrypt – Authentication & authorization
- 📦 Redux Toolkit + React-Redux – Global state management
- 📝 React Hook Form – Forms (bookings, login, signup)
- 🛣️ React Router – Navigation

---

## Feature Description

1. 🔐 **User Authentication** – Users, renters, and admins register/login securely using JWT + bcrypt.
2. 👥 **Role-Based Access** – Admin (full control), Renter (manage listings), Guest (book stays & review).
3. 🏠 **Property Listing** – Renters add, update, delete, and view property details including images.
4. 🔍 **Property Search & Filter** – Guests search/filter by location, price, dates, and amenities.
5. 📅 **Booking Management** – Guests can book stays; Renters view/manage reservations.
6. ❌ **Booking Cancellation** – Guests can cancel bookings; Admin can manage cancellations.
7. 💳 **Payment Processing** – Secure online payments via Razorpay; Admin can track payments.
8. 📧 **Email Notifications** – Automatic email confirmations for bookings, payments, and cancellations.
9. ⭐ **Reviews & Ratings** – Guests leave reviews and ratings; Renters can respond.
10. 🛠️ **Admin Dashboard** – Admin manages users, properties, bookings, and payments.

---
## Quick Start

### Installation

Install the project dependencies:

```bash
npm install
```

# BACKEND .ENV

- PORT=
- MONGO_URL=
- JWT_SECRET_KEY=
- NODEMAILER_APP_PASSWORD=
- NODEMAILER_MAIL=
- RAZORPAY_KEY_ID=
- RAZORPAY_KEY_SECRET=

# FRONTEND .ENV

- VITE_RAZORPAY_KEY_ID=

Replace the values with your actual credentials.

---

## Running the Project

### Backend

```bash
npx nodemon
```

## Frontend
```bash
npm run dev
```









