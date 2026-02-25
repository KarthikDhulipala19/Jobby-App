# 🚀 Jobby App

A modern job-search platform built with **React**, featuring authentication, job browsing, filtering, and secure protected routes.

---

## 📌 Overview

**Jobby App** is a user-friendly application designed for job seekers to explore job listings, view detailed job descriptions, and filter opportunities based on their preferences.  
The app includes secure authentication, smooth navigation, and dynamic data fetching using JWT-based API authorization.

---
## Link To Jobby App

Link - <a href='https://sitaramajobby.ccbp.tech/' target='_blank'>https://sitaramajobby.ccbp.tech/</a>




---

## 🔥 Features

### 🔐 User Authentication
- Login with username & password  
- API-based authentication  
- JWT Token stored in cookies  
- Token included in all authorized API requests  

### 📍 Routing & Navigation
- Built using **React Router**  
- Pages: **Login**, **Home**, **Jobs**, **Job Item Details**  
- Uses `Route`, `Switch`, and `Link`  
- **Protected Routes** redirect unauthorized users to Login  

### 🔍 Job Search & Filters
- Search jobs by title or keyword  
- Filter by:
  - Employment Type  
  - Salary Range  
- Filters passed as query parameters for API requests  

### 🛡️ Security
- Protected routes validated via JWT  
- Redirects unauthenticated users  
- Secure cookie handling for token management  

### 💻 User Interface
- Responsive and modular UI  
- Uses reusable React components  
- Proper state management, props handling, controlled inputs  

---

## 🛠️ Technologies Used

- React JS  
- JavaScript (ES6+)  
- React Router  
- REST API  
- JWT Authentication  
- Cookies  
- CSS  
- Local Storage (where applicable)  

---

## 📁 JobbyApp Structure/
      ├── public/
      │ └── index.html
      │
      ├── src/
      │ ├── components/
      │ │ ├── FiltersGroup/
      │ │ ├── Header/
      │ │ ├── Home/
      │ │ ├── JobCard/
      │ │ ├── JobItemDetails/
      │ │ ├── Jobs/
      │ │ ├── Login/
      │ │ ├── NotFound/
      │ │ ├── ProfileDetails/
      │ │ ├── ProtectedRoute/
      │ │ └── SimilarJobCard/
      │ │
      │ ├── App.css
      │ ├── App.js
      │ ├── index.js
      │ └── setupTests.js
      │
      └── .git/
