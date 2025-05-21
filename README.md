# OrganicDental

# 🦷 Organic Dental Website

Welcome to the **Organic Dental** full-stack web application — a modern dental care platform designed to simplify patient interaction, appointment booking, and administrative control. Built with a professional interface and essential features for both patients and clinic admins.

---

##  Live Demo

Visit the live site: https://organicdental-1.onrender.com/
Admin Panel:https://organicdental-1.onrender.com/admin

Admin credentials: 
Username: amiramalek006@gmail.com	
Password: Amira@1234
Since it's render /admin functionality do not work, instead click on login on website and enter the login credentials shared above

---


organic-dental/


├── client/ # React frontend

├── server/ # Node.js backend with Express

├── docs/ # All project documents (Proposal, Schema, User Flow)

├── README.md # Project overview

---

You can find all documents related to the project in the [docs/](./docs) directory:

- Project Proposal
- Initial Ideas
- Schema Design
- User Flow

  
---

## Tech Stack

**Frontend**
- React.js
- React Router DOM
- Tailwind CSS (or Bootstrap)
- Google Maps API integration

**Backend**
- Node.js / Express
- MongoDB + Mongoose
- JWT-based Authentication

**Deployment**
- Render (Backend & Frontend)
- MongoDB Atlas (Database)

---

##  Features

###  Patient-Facing
- Book appointments online
- View services offered
- Contact dental office via direct call buttons
- Interactive Google Map for location and directions
- Connect via social media links
- Register/Login to access personal dashboard
- Submit reviews and feedback

###  Admin Panel
- Admin login authentication
- Manage users (view, delete, update roles)
- Manage appointments
- Manage and list services
- View user reviews
- Dashboard insights (overview cards and stats)

---

##  Folder Structure


Admin can promote users to different roles
MongoDB integration for user data

React frontend with dynamic routing

**API Documentation**
Base URL: https://organicdental.onrender.com/api

**Auth APIs**
POST /auth/register – Register a new user

POST /auth/login – Authenticate and receive a JWT token

**Post APIs**
POST /posts – Add a new post (supports image)

GET /posts – Fetch all posts

GET /posts/:slug – Fetch post by slug

PUT /posts/:postId – Update a post

DELETE /posts/:postId – Delete a post

**Service APIs**
POST /services – Add a new service (supports image)

GET /services – Fetch all services

PUT /services/:serviceId – Update a service

DELETE /services/:serviceId – Delete a service

**User APIs**
POST /users – Add a new user (admin only)

GET /users – Get all users

GET /users/:userId – Get specific user

PUT /users/:userId – Update user info

DELETE /users/:userId – Delete user

**Appointment APIs**
POST /appointments – Book appointment

GET /appointments – Get all appointments (admin)

GET /appointments/my – Get current user's appointments

PUT /appointments/:id/status – Change status

DELETE /appointments/:id – Delete appointment

**Review APIs**
POST /reviews – Submit a review

GET /reviews – Get all reviews (admin)

DELETE /reviews/:id – Delete a review

**Utility**
apiCallWithToken() – Utility function to call protected endpoints with token in header

---

**About This Project**

This application was developed as part of my Capstone Project for the Software Engineering Career Track at [Springboard / University of Maryland Global Campus (UMGC)].

Organic Dental is a full-stack web application designed for a modern dental practice. It demonstrates my ability to build secure, scalable, and user-friendly applications using current technologies in frontend, backend, API integration, and database management.

---

**Author**
Amira Malek  
[LinkedIn Profile](https://www.linkedin.com/in/amira-malek-733301307/)

