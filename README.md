# 🍽️ DineHub – Full-Stack Restaurant Table Booking Platform

DineHub is a full-stack multi-restaurant table booking platform that allows users to discover restaurants, search for restaurants, view restaurant details, check available tables, and make table reservations online.

The platform also provides an admin dashboard where administrators can manage restaurants and monitor recent bookings.

---

## 📌 Project Overview

DineHub is designed to simplify the restaurant reservation process by providing a centralized platform for discovering restaurants and booking tables online.

Instead of contacting restaurants manually or waiting for confirmation, users can browse available restaurants, select a preferred date and time, choose a table, and create a reservation through the platform.

The project demonstrates the implementation of a modern full-stack web application using React, Node.js, Express.js, and MongoDB.

---

## 🎯 Objectives

The main objectives of DineHub are:

- To provide an easy-to-use restaurant discovery platform.
- To allow users to search for restaurants.
- To display restaurant information and available tables.
- To provide an online table reservation system.
- To implement secure user authentication.
- To allow users to view their bookings.
- To provide an admin dashboard for restaurant management.
- To allow administrators to monitor recent bookings.
- To build a responsive and user-friendly web interface.
- To demonstrate full-stack development using REST APIs.

---

## ✨ Features

### 👤 User Features

- User registration
- User login and authentication
- Restaurant listing
- Restaurant search
- Restaurant details
- Table availability
- Date and time selection
- Online table booking
- Booking confirmation
- My Bookings section
- Responsive user interface
- Logout functionality

### 👨‍💼 Admin Features

- Admin authentication
- Admin dashboard
- Restaurant management
- Add new restaurant
- View restaurant information
- Monitor recent bookings
- Booking overview
- Dashboard statistics

---

## 🛠️ Technologies Used

### Frontend

- React.js
- Vite
- JavaScript
- HTML5
- CSS3
- React Router

### Backend

- Node.js
- Express.js
- REST API
- JWT Authentication

### Database

- MongoDB
- Mongoose

### Development Tools

- Visual Studio Code
- Git
- GitHub
- Postman
- npm
- Chrome Developer Tools

### Deployment

- Vercel – Frontend
- Render – Backend
- MongoDB Atlas – Database

---

## 🏗️ Project Architecture

DineHub follows a client-server architecture.

```text
                    ┌─────────────────────┐
                    │       User          │
                    │   Web Browser       │
                    └──────────┬──────────┘
                               │
                               ▼
                    ┌─────────────────────┐
                    │ React.js Frontend   │
                    │       Vite          │
                    └──────────┬──────────┘
                               │
                         REST API Calls
                               │
                               ▼
                    ┌─────────────────────┐
                    │ Node.js + Express   │
                    │      Backend        │
                    └──────────┬──────────┘
                               │
                               ▼
                    ┌─────────────────────┐
                    │      MongoDB        │
                    │      Database       │
                    └─────────────────────┘


                    