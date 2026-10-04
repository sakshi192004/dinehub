# DineHub – Full-Stack Multi-Restaurant Table Booking Platform

DineHub is a full-stack restaurant discovery and table-booking MVP built with React, Express, Node.js and MongoDB.

## Features
- Restaurant listing and search
- Restaurant detail page
- Table availability and booking
- User registration/login with JWT
- My Bookings page
- Admin dashboard for restaurants and bookings
- Responsive modern UI
- MongoDB models and REST APIs

## Run locally
### 1. Server
```bash
cd server
npm install
copy .env.example .env
npm run dev
```
Set `MONGO_URI` in `.env`. If MongoDB is unavailable, the server runs with an in-memory demo dataset so the UI can still be tested.

### 2. Client
```bash
cd client
npm install
npm run dev
```
Open http://localhost:5173

Demo admin login: `admin@dinehub.com` / `admin123`

## Project structure
- `client` – React + Vite frontend
- `server` – Express REST API, JWT auth and MongoDB models
