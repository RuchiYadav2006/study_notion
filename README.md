# 📚 StudyNotion - EdTech Platform

<p align="center">
  <img src="https://img.shields.io/badge/MongoDB-%234ea94b.svg?style=for-the-badge&logo=mongodb&logoColor=white" alt="MongoDB" />
  <img src="https://img.shields.io/badge/express.js-%23404d59.svg?style=for-the-badge&logo=express&logoColor=%2361DAFB" alt="Express.js" />
  <img src="https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB" alt="React" />
  <img src="https://img.shields.io/badge/node.js-6DA55F?style=for-the-badge&logo=node.js&logoColor=white" alt="Node.js" />
</p>

**StudyNotion** is a full-stack MERN application designed to manage study content, courses, and user progress. It provides a structured platform for learning with secure authentication, seamless course handling, and visual progress tracking.

---

## 📑 Table of Contents
- [Features](#-features)
- [Tech Stack](#-tech-stack)
- [Getting Started](#-getting-started)
- [Environment Variables](#-environment-variables)
- [Running the App](#-running-the-application)
- [Project Structure](#-project-structure)
- [Author](#-author)

---

## ✨ Features

- **🔐 User Authentication:** Secure login and registration utilizing JWT (JSON Web Tokens).
- **📚 Course Management:** Create, manage, and consume structured course content.
- **📈 Progress Tracking:** Visual indicators to track user progression through course modules.
- **☁️ Image Upload Support:** Integrated with Cloudinary for seamless media storage and retrieval.
- **📧 Email/OTP Support:** Configured for email verification and OTPs using NodeMailer.
- **💻 Responsive UI:** A clean, accessible, and fully responsive user interface that works across all devices.

---

## 🚀 Tech Stack

- **Frontend:** React.js
- **Backend:** Node.js, Express.js
- **Database:** MongoDB
- **Services:** Cloudinary (Media), JWT (Auth)

---

## 🛠️ Getting Started

Follow these steps to set up the project locally on your machine.

### 1. Clone the Repository
```bash
git clone [https://github.com/RuchiYadav2006/study_notion.git](https://github.com/RuchiYadav2006/study_notion.git)
cd study_notion
2. Install Dependencies
Install Frontend Dependencies:
npm install
Install Backend Dependencies:
cd server
npm install
cd ..


⚙️ Environment Variables
To run this project, you will need to add environment variables to your backend.

Create a file named .env in the root of the server directory.

Open .env.example to see the required keys.

Copy all variables from .env.example and paste them into your new .env file.

Fill in the required values.

✅ Required Variables (Mandatory)
MONGODB_URL: Get this from your MongoDB Atlas dashboard.

JWT_SECRET: Generate a random secure string for your tokens.

🟡 Optional Variables (Feature-Based)
Note: Use a Gmail App Password instead of your actual email password for MAIL_PASS.

▶️ Running the Application
You will need to run the client and the server simultaneously. Open two separate terminal windows.

Terminal 1: Start the Backend Server

Terminal 2: Start the Frontend App

📂 Project Structure
study_notion/
│
├── src/                # Frontend (React components, pages, styles)
├── server/             # Backend (Node.js, Express routes, models, controllers)
├── public/             # Static files
├── .env.example        # Environment variables reference template
├── package.json        # Project metadata and dependencies
└── README.md           # Project documentation

📌 Notes:

The .env file is intentionally excluded from GitHub for security reasons. Always create your own .env file before running the application.

The node_modules folders are not included to keep the repository lightweight. Running npm install generates these locally.

👩‍💻 Author
Ruchi Yadav GitHub: RuchiYadav2006

⭐ Support
If you found this project helpful, learned something new, or used it as a reference, please consider giving it a ⭐ on GitHub!
