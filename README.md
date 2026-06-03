# On-Demand Home Services Platform

A full-stack MERN application for booking and managing home services online. The platform includes separate user and admin panels with authentication, service management, and online payment integration.

## Features

* User authentication using JWT
* Service booking and management
* Admin dashboard
* Razorpay payment integration
* REST API integration
* Responsive user interface
* MongoDB database operations

## Tech Stack

### Frontend

* React.js
* Tailwind CSS
* JavaScript

### Backend

* Node.js
* Express.js

### Database

* MongoDB

## Tools Used

* Git & GitHub
* Postman
* MongoDB Compass
* VS Code

## Project Structure

```bash
backend/
admin/
user/
```

## Installation

### Clone Repository

```bash
git clone https://github.com/gohilteena/on-demand-home-services-platform.git
```

### Install Backend Dependencies

```bash
cd backend
npm install
```

### Install Frontend Dependencies

```bash
cd admin
npm install

cd ../user
npm install
```

## Environment Variables

Create `.env` file inside backend folder:

```env
PORT=8000
MONGO_URI=your_mongodb_uri
JWT_SECRET=your_jwt_secret
RAZORPAY_KEY_ID=your_key
RAZORPAY_KEY_SECRET=your_secret
```

## Run Project

### Backend

```bash
cd backend
npm start
```

### Admin Frontend

```bash
cd admin
npm start
```

### User Frontend

```bash
cd user
npm start
```

## Author

Teena Gohil
