# WorkoutApp

A comprehensive fitness application with React frontend, Node.js/Express backend, and Python Flask microservices.

## Table of Contents
- [Project Overview](#project-overview)
- [Features](#features)
- [Tech Stack](#tech-stack)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Environment Setup](#environment-variables)
- [Running the Application](#running-the-application)
- [Project Structure](#project-structure)
- [Contributing](#contributing)
- [License](#license)

## Project Overview

WorkoutApp is a full-stack fitness application designed to provide personalized workout plans, diet suggestions, and user tracking. The application leverages modern web technologies to create an intuitive and responsive user experience.

## Features

### Frontend (React)
- User Authentication (Login/Register)
- Interactive workout plan interface
- Dynamic diet suggestion system
- Responsive design
- Real-time API data integration

### Backend (Node.js/Express)
- Secure JWT-based authentication
- CRUD operations for workout and diet plans
- MongoDB database integration
- User profile management
- File upload capabilities (via Cloudinary)

### Flask Microservice
- Machine learning-powered workout recommendations
- Advanced data processing
- Additional API endpoints for specialized functionality

## Tech Stack

- **Frontend**: React, Vite
- **Backend**: Node.js, Express.js
- **Database**: MongoDB
- **Authentication**: JSON Web Tokens (JWT)
- **File Storage**: Cloudinary
- **Microservices**: Python Flask
- **State Management**: TBD (Redux/Context API)
- **Styling**: TBD (Tailwind/Material UI)

## Prerequisites

Before you begin, ensure you have the following installed:
- Node.js (v16+ recommended)
- npm (v8+)
- Python 3.8+
- MongoDB

## Installation

### Clone the Repository
```bash
git clone https://github.com/rithesh10/workout2.git
### Install Dependencies
```
#### Frontend
```bash
cd frontend
npm install
```

#### Backend
```bash
cd backend
npm install
```

#### Flask Microservice
```bash
cd flask
pip install -r requirements.txt
```

## Environment Variables

### Frontend (.env)
```
VITE_BACKEND_URL=http://localhost:5000
VITE_FLASK_URL=http://localhost:5001
```

### Backend (.env)
```
PORT=5000
MONGODB_URI=mongodb://localhost:27017/workoutapp
CORS_ORIGIN=http://localhost:3000
ACCESS_TOKEN_SECRET=your_secret_key
ACCESS_TOKEN_EXPIRY=1d
REFRESH_TOKEN_SECRET=your_refresh_secret
REFRESH_TOKEN_EXPIRY=7d
CLOUDINARY_CLOUD_NAME=your_cloudinary_name
CLOUDINARY_CLOUD_KEY=your_cloudinary_key
CLOUDINARY_CLOUD_SECRET=your_cloudinary_secret
API_KEY=your_api_key
```

## Running the Application

### Development Mode

#### Frontend
```bash
cd frontend
npm run dev
```

#### Backend
```bash
cd backend
npm run dev
```

#### Flask Microservice
```bash
cd flask-service
python app.py
```

### Production Build

#### Frontend
```bash
cd frontend
npm run build
```

#### Backend
```bash
cd backend
npm start
```

## Project Structure
```
WorkoutApp/
│
├── frontend/             # React application
│   ├── src/
│   ├── public/
│   └── vite.config.js
│
├── backend/              # Node.js Express backend
│   ├── controllers/
│   ├── models/
│   ├── routes/
│   └── middleware/
│
└── flask-service/        # Python Flask microservice
    ├── ml_models/
    ├── routes/
    └── app.py
```

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

Distributed under the MIT License. See `LICENSE` for more information.

## Contact

akshaydevaraboina410@gmail.com

