# MERN Trello Clone

> **MERN Stack Trello Clone with Real-time Collaboration and Drag-and-Drop Functionality**

[![Live Demo](https://img.shields.io/badge/🚀_Live_Demo-Visit_Here-2ea44f?style=for-the-badge)](https://trello-web-eight-self.vercel.app)

## Overview

This project is a **Trello clone built with the MERN stack (MongoDB, Express.js, React, Node.js)**, featuring real-time collaboration, drag-and-drop interfaces, and secure email-based authentication. It replicates core Trello functionalities like board management, column/card organization, and team invitations.

**Frontend:** React + Vite ([Demo](https://trello-web-eight-self.vercel.app))  
**Backend:** Node.js + Express + MongoDB ([API](https://trello-ideft-api.onrender.com))


## Key Features

- 📧 Email registration with Brevo verification (account activation required)  
- 🌙 Dark, Light, and System mode  
- 📊 Board management: create, delete and search boards  
- 👥 Profile settings: password change, display name, avatar upload  
- 🤝 Real-time invitations: invite users by email (Socket.IO) with accept/reject  
- ➕ Add new columns and cards; drag-and-drop using @dnd-kit  
- 🃏 Card details: cover images, assign members, description, comments, rename, delete  
- 🔐 JWT-based authentication for secure sessions  
- 📱 Responsive UI (Material-UI)  
- 🔔 Real-time notifications with React Toastify


## Demo Users

| Email                   | Password       |
|-------------------------|----------------|
| `nguyencongthong.work@gmail.com`  | `12345678a`    |


## Run Locally


This project requires Node.js 18.16.0:


**Frontend** (`http://localhost:5173`)
```bash
cd trell-web
yarn install
yarn dev
```

**Backend** (`http://localhost:8017`)
```bash
cd trello-api
yarn install
yarn dev
```

## Technology Stack
- **Frontend**: React, Vite, Material-UI, @dnd-kit, Redux Toolkit, React Toastify
- **Backend**: Node.js, Express, MongoDB, JWT, Socket.IO, Brevo, Cloudinary, Multer, Joi
- **Deployment**: Vercel (frontend), Render (backend)

## Project Flow
- **Register**: Email signup → Brevo verification → account activation
- **Login**: JWT issued → access boards and profile
- **Board** & Column: Create/delete/search boards → add columns → drag-and-drop
- **Card**: Add new cards → cover, members, description, comment, rename, delete
- **Realtime** Collaboration: Invite users → accept/reject → live updates and notifications

## Documentation (README full)
👉 [Project Details](./README.full.md)


