<div align="center">
  <img src="creative-auth-bartender/client/src/assets/WDrunk Logo@300x.png" alt="WDrunk Logo" width="200" height="400">
</div>


# The Drunken Giraffe 

A comprehensive MERN stack e-commerce **web application** that revolutionizes user authentication through an innovative bottle-sorting game while delivering a complete online liquor store experience. This full-stack web platform combines traditional e-commerce functionality with creative gamified authentication, featuring product management, shopping cart capabilities, user reviews and accessibility-first design principles.

**Authors:** Angie Van Rooyen | Dhiali Chetty | Xander Poalses

<div align="center">
  <img src="creative-auth-bartender/client/src/assets/drunken mock up.png" alt="Mock up" >
</div>

## 📌 Table of Contents

- [Design & Development Process](#design--development-process)
- [Project Overview](#project-overview)  
- [Features](#features)  
- [Tech Stack](#tech-stack)  
- [Creative Authentication Explained](#creative-authentication-explained)  
- [Getting Started](#getting-started)  
- [API Documentation](#api-documentation)  
- [Folder Structure](#folder-structure)  
- [Demo](#demo)  
- [Contributing](#contributing)  
- [License](#license)

---
## 🛠️ Built With

### Frontend
![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![Bootstrap](https://img.shields.io/badge/Bootstrap-563D7C?style=for-the-badge&logo=bootstrap&logoColor=white)

### Backend
![Node.js](https://img.shields.io/badge/Node.js-43853D?style=for-the-badge&logo=node.js&logoColor=white)
![Express.js](https://img.shields.io/badge/Express.js-404D59?style=for-the-badge)
![MongoDB](https://img.shields.io/badge/MongoDB-4EA94B?style=for-the-badge&logo=mongodb&logoColor=white)
![JWT](https://img.shields.io/badge/JWT-black?style=for-the-badge&logo=JSON%20web%20tokens)

### Tools & Libraries
![NPM](https://img.shields.io/badge/NPM-%23000000.svg?style=for-the-badge&logo=npm&logoColor=white)
![Git](https://img.shields.io/badge/git-%23F05033.svg?style=for-the-badge&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)
![VS Code](https://img.shields.io/badge/Visual%20Studio%20Code-0078d4.svg?style=for-the-badge&logo=visual-studio-code&logoColor=white)
![Swagger](https://img.shields.io/badge/-Swagger-%23Clojure?style=for-the-badge&logo=swagger&logoColor=white)

---
## 🚀 Getting Started

### Prerequisites

Before running this project, ensure you have the following installed on your system:

**Required Software:**
- **Node.js** (v16.0 or higher) - [Download here](https://nodejs.org/)
- **npm** (v8.0 or higher) - Comes with Node.js
- **Git** - [Download here](https://git-scm.com/)
- **MongoDB Atlas Account** - [Create free account](https://www.mongodb.com/atlas)
- **Code Editor** (VS Code recommended) - [Download here](https://code.visualstudio.com/)

**API Keys & Accounts:**
- MongoDB Atlas connection string (free tier available)
- JWT Secret key (you'll create this)

**Minimum System Requirements:**
- RAM: 4GB minimum, 8GB recommended
- Storage: 500MB free space
- Operating System: Windows 10+, macOS 10.14+, or Linux

### How to Install

Follow these steps to get the project running locally:

#### 1. Clone the Repository

```bash
git clone https://github.com/Dhiali/mern_liquor.git
cd mern_liquor/creative-auth-bartender
```

#### 2. Backend Setup

```bash
# Navigate to server directory
cd server

# Install backend dependencies
npm install

# Create environment file
# Create a .env file in the server directory with the following:
```

Create a `.env` file in the `server` directory:

```env
PORT=5000
MONGO_URI=mongodb+srv://your_username:your_password@cluster.mongodb.net/drunken_giraffe
JWT_SECRET=your_super_secret_jwt_key_here
NODE_ENV=development
```

**MongoDB Setup:**
1. Go to [MongoDB Atlas](https://www.mongodb.com/atlas)
2. Create a free account and new cluster
3. Get your connection string from "Connect" → "Connect your application"
4. Replace `your_username`, `your_password`, and cluster details in the MONGO_URI

#### 3. Frontend Setup

Open a new terminal window:

```bash
# Navigate to client directory (from project root)
cd creative-auth-bartender/client

# Install frontend dependencies
npm install
```

#### 4. Start Development Servers

**Backend Server (Terminal 1):**
```bash
cd server
npm run dev
```
The backend will run on `http://localhost:5000`

**Frontend Server (Terminal 2):**
```bash
cd client
npm start
```
The frontend will run on `http://localhost:3000`

#### 5. Verify Installation

- Backend: Visit `http://localhost:5000/apiDocumentation` for Swagger API docs
- Frontend: Visit `http://localhost:3000` to see the application
- Test the connection by registering a new user

---

## 🧾 API Documentation

Swagger UI is available for testing all backend routes.

Once the backend server is running, visit:  
[http://localhost:5000/apiDocumentation](http://localhost:5000/apiDocumentation)

This interface allows you to test endpoints like login, register, and game results directly from the browser.

---

## ✨ Project Features

### 🎯 Main Features & Functionality

#### 🔐 Authentication System
- **🎮 Gamified Login (Spirited Sign-In)** - Interactive bottle-sorting game where users drag and drop virtual liquor bottles into correct categories to authenticate
- **♿ Accessibility Login** - Traditional form-based login fallback ensuring inclusive access for all users
- **🔑 Secure Registration** - User account creation with email verification and password validation
- **🛡️ JWT Authentication** - Token-based authentication system with automatic session management
- **🔒 Password Security** - bcrypt hashing for secure password storage and validation

#### 🛒 E-Commerce Platform
- **📦 Product Management** - Complete CRUD operations for liquor inventory management
- **🛍️ Shopping Cart** - Add, remove, and modify product quantities with persistent cart state
- **💳 Checkout Process** - Streamlined purchasing workflow with order confirmation
- **⭐ Product Reviews** - User rating system (0-5 stars) with written reviews and comments
- **❤️ Product Interactions** - Like/unlike functionality and social engagement features

#### 👥 User Management
- **🏷️ Role-Based Access** - Admin and customer roles with appropriate permissions
- **👤 User Profiles** - Customizable profiles with profile picture uploads
- **📊 Admin Dashboard** - Product approval workflow and user management tools
- **📈 User Analytics** - Track user engagement and purchase history

#### 🔍 Advanced Features
- **🎯 Smart Filtering** - Filter products by category, price, rating, and availability
- **🔎 Search Functionality** - Real-time product search with auto-suggestions
- **📱 Responsive Design** - Mobile-first design optimized for all device types
- **🎨 Custom UI Components** - Drag-and-drop interface with smooth animations
- **📊 Progress Tracking** - Visual feedback for game completion and purchase flows

#### 🛠️ Technical Features
- **📋 REST API** - Comprehensive RESTful API architecture with full CRUD operations
- **📚 API Documentation** - Interactive Swagger documentation for all endpoints
- **🗄️ Database Integration** - MongoDB with Mongoose ODM for efficient data management
- **🔄 Real-time Updates** - Dynamic content updates without page refreshes
- **⚡ Performance Optimization** - Efficient data loading and caching strategies

### 🌟 Additional Innovative Features
- **🎪 Creative UX Design** - Unique authentication experience that stands out from traditional login systems
- **🎵 Interactive Feedback** - Visual and audio cues during the bottle-sorting game
- **📐 Accessibility Standards** - WCAG compliant design with screen reader support
- **🔗 Social Integration** - Share favorite products and achievements
- **📱 Progressive Web App** - App-like experience with offline capabilities

---

## 🎨 Design & Development Process

<div align="center">
  <a href="[YOUR_FIGMA_LINK_HERE]" target="_blank">
    <img src="https://img.shields.io/badge/Figma-F24E1E?style=for-the-badge&logo=figma&logoColor=white" alt="View Design Process">
  </a>
</div>

**📋 View our complete design and planning process including:**
- 🎨 **Wireframes & Mockups** - Initial layout designs and user interface planning
- 🌈 **Moodboards** - Visual inspiration and brand identity development  
- 🗺️ **User Journey Maps** - Authentication flow and user experience mapping
- 📊 **Database Schema Planning** - Data structure and relationship design
- 🎯 **Feature Planning** - Sprint planning and development roadmap
- 🔄 **Iteration Process** - Design evolution and feedback implementation

*Click the Figma badge above to explore our full design documentation and development process.*

---

## 📁 Folder Structure

```
mern_liquor/
│
├── creative-auth-bartender/
│   ├── server/
│   │   ├── config/
│   │   ├── controllers/
│   │   ├── models/
│   │   ├── routes/
│   │   ├── middleware/
│   │   ├── utils/
│   │   ├── server.js
│   │   ├── .gitignore
│   │   └── .env
│   │
│   ├── client/
│   │   ├── public/
│   │   ├── src/
│   │   │   ├── assets/
│   │   │   ├── components/
│   │   │   ├── pages/
│   │   │   ├── styles/
│   │   │   └── App.js
│   │   └── package.json
│   │
│   └── README.md
```

---

## 🎥 Demo

A short 5-minute video demo shows:

- Registering and logging in
- Game-based authentication in action
- Accessibility fallback login
- API and backend overview

[Link To Demonstration Video](https://drive.google.com/drive/folders/1Y0wYQVNzQextt4zcyJ20wf5Buxe7BxJJ?usp=sharing)


---

## 🤝 Contributing

Contributions, issues, and feature requests are welcome!

1. Fork the repo
2. Create your branch (`git checkout -b feature-name`)
3. Commit your changes (`git commit -m 'Add feature'`)
4. Push to the branch (`git push origin feature-name`)
5. Open a pull request

---

## 📜 License

MIT © 2025 BugSquashers
