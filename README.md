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

## ✨ Features

- 🎮 Game-based login challenge (Spirited Sign-In)
- 🧑‍🦽 Accessible fallback login form
- 🔐 JWT token-based authentication
- 🔑 Password hashing using `bcryptjs`
- 🗃️ MongoDB integration
- 📄 REST API with Swagger documentation
- 📦 Fully modular and scalable codebase

---

## 🧪 Creative Authentication Explained

### 🥃 Spirited Sign-In

During login, users sort a series of drink bottles correctly in a game interface. Success grants access; failure shows a retry screen.

- **Why it’s creative:**  
  It uses **spatial memory, visual cues**, and **pattern matching** instead of traditional typing. It gamifies identity verification without compromising security.

- **Fallback option:**  
  A basic accessible login form is available at `/accessibility-login`.

---

## 🚀 Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/AngievR05/mern_liquor.git
cd mern_liquor/creative-auth-bartender
```

### 2. Install dependencies

```bash
# Install backend dependencies
cd server
npm install

# Install frontend dependencies
cd ../client
npm install
```

### 3. Setup your environment variables

Create a `.env` file in the `server` directory and add the following:

```
PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_super_secret_jwt_key
```

Make sure to add `.env` to your `.gitignore` file so that sensitive information is not committed to GitHub.

---

### 4. Start the development servers

```bash
# Start backend server
cd server
npm run dev

# Start frontend server
cd ../client
npm start
```

---

## 🧾 API Documentation

Swagger UI is available for testing all backend routes.

Once the backend server is running, visit:  
[http://localhost:5000/apiDocumentation](http://localhost:5000/apiDocumentation)

This interface allows you to test endpoints like login, register, and game results directly from the browser.

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
