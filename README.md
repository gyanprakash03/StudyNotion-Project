# StudyNotion

StudyNotion is a fully functional ed-tech platform designed to provide a seamless and interactive learning experience for students while offering instructors a space to showcase their expertise and connect with learners globally. Built using the MERN stack (MongoDB, ExpressJS, ReactJS, and NodeJS), this platform combines robust architecture with an intuitive user interface.

## Table of Contents
1. [Features](#features)  
2. [System Architecture](#system-architecture)  
3. [Tech Stack](#tech-stack)  
4. [Setup and Installation](#setup-and-installation)   
5. [API Design](#api-design)  
6. [Deployment](#deployment)  
7. [Testing](#testing)  
8. [Future Enhancements](#future-enhancements)  
9. [Contact](#contact)
10. [Screenshots](#screenshots)

---

## Features

### For Students
- Browse and search courses.
- Wishlist and purchase courses.
- Consume course content (videos, documents, etc.).
- Manage profile and account details.

### For Instructors
- Create, update, and delete courses.
- Manage course content and pricing.
- Track performance with dashboards and insights.

### General Features
- User authentication with OTP and password reset functionality.
- Razorpay payment integration for secure transactions.
- Cloud-based media management using Cloudinary.

---

## System Architecture

The platform follows a **client-server architecture** comprising three main components:

### Front-End
- Built with **ReactJS**, delivering dynamic and responsive user interfaces.
- Communicates with the back end using **RESTful APIs**.

### Back-End
- Powered by **Node.js** and **Express.js** for scalable and secure server-side functionality.
- Provides APIs for features like user authentication, course management, and payment handling.

### Database
- **MongoDB** for flexible, scalable storage of course content and user data.
- Stores unstructured and semi-structured data like videos, images, and documents.

### Architecture Diagram
*(Insert your architecture diagram here)*

---

## Tech Stack
- **Front-End:** ReactJS, Tailwind CSS  
- **Back-End:** Node.js, Express.js  
- **Database:** MongoDB  
- **Authentication:** JWT, Bcrypt  
- **Cloud Storage:** Cloudinary  
- **Payment Gateway:** Razorpay  

---

## Setup and Installation

### Clone the repository:
```bash
git clone https://github.com/gyanprakash03/StudyNotion-Project 
cd StudyNotion  
```
### Install dependencies:
For the backend:
```bash
cd Server  
npm install
```
For the frontend:
```bash
cd Client  
npm install
```
### Configure environment variables:
Create a .env file in the Server directory.
Add the following:
```env
MONGO_URI=<your-mongodb-uri>  
JWT_SECRET=<your-jwt-secret>  
CLOUDINARY_URL=<your-cloudinary-url>  
RAZORPAY_KEY_ID=<your-razorpay-key-id>  
RAZORPAY_KEY_SECRET=<your-razorpay-key-secret>
```
---

## API Design
The platform's back end provides a comprehensive set of APIs. Key functionalities include:

### User Authentication
- Signup, login, OTP verification, and password recovery.
### Course Management
- CRUD operations for courses and content.
### Payment Integration
- Secure checkout using Razorpay.

---

## Deployment
The platform is deployed in the following environment:

- Backend hosted on **Render**
- Frontend hosted on **Vercel**
- Database hosted on **MongoDB Atlas**

---

## Testing
- End-to-end testing for overall functionality.
- Postman used for API testing.

---

## Future Enhancements

- **Gamification**: Add badges and rewards to enhance student engagement.
- **Live Sessions**: Enable real-time interaction between students and instructors.
- **Search Functionality**: Add a global search feature for courses, instructors, and content.

---

## Contact
For inquiries, please contact: gyan091203@gmail.com

---

## Screenshots

![Screenshot1](src/assets/Images/Screenshot%202025-01-24%20191311.png)
-
![Screenshot2](src/assets/Images/Screenshot%202025-01-24%20191347.png)
-
![Screenshot2](src/assets/Images/Screenshot%202025-01-24%20191439.png)
-
