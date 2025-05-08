# Social Dash: Social Media Dashboard & Authentication System

## 📌 Project Overview

**Social Dash** is a modern, secure social media management dashboard that integrates a **React frontend** with a **Django backend**. It includes a complete authentication system, laying the groundwork for future social media tools like post scheduling and analytics.

### 🚀 Core Functionality
- Register new users
- Login with email and password
- Secure logout
- Access protected dashboard content

---

## 🔐 Key Features

### ✅ Authentication System
- User registration with email, username, and password
- Secure login/logout with session-based authentication
- CSRF protection for all forms
- Protected routes that require login
- Auth state management using Context API

### 🖥️ Frontend (React)
- Responsive UI built with **Material-UI**
- Dynamic nav based on auth status
- Form validation & error feedback
- API interaction using Axios

### ⚙️ Backend (Django REST Framework)
- Custom user model (email as username)
- REST API for auth (login, logout, register)
- Django session authentication
- CORS setup for local dev
- CSRF token enforcement

---

## 🧰 Technical Stack

### Frontend
- React.js (Hooks + Context)
- React Router
- Material-UI
- Axios

### Backend
- Django 4+
- Django REST Framework
- Custom User Model
- CORS Headers

---

## 🔐 Security Highlights
- CSRF tokens on all POST/PUT/DELETE requests
- Session cookies with `HttpOnly` and `SameSite` attributes
- Strong password hashing
- Route protection with 401 fallback

---

## 👤 User Flow

| User Type         | Actions                                                                 |
|------------------|-------------------------------------------------------------------------|
| **Unauthenticated** | Register, Login, View public pages                                     |
| **Authenticated**   | Access dashboard, View content, Logout securely                       |

---

## 📈 Future Enhancements
This system will serve as the base for:
- Connecting to social media APIs (Twitter, Instagram, etc.)
- Scheduling posts
- Viewing engagement and analytics

---

## 📄 License
This project is licensed under the MIT License.

