# 🚀 NovaCore - Online Code Editor Platform

<div align="center">

![NovaCore Logo](frontend/public/mainLogo.png)

### Code • Compile • Create • Convert

An advanced cloud-based code editor built with the **MERN Stack** that allows users to write, execute, and test code directly from the browser. NovaCore also includes productivity tools such as **Image-to-Text (OCR)** and **Voice-to-Text Conversion**.

</div>

---

## 📌 Overview

NovaCore is a full-stack web application designed to provide a seamless coding experience for developers and students. Users can write, edit, and execute code in multiple programming languages while also utilizing AI-powered utilities like OCR and speech recognition.

---

## ✨ Features

### 💻 Online Code Editor
Supports multiple programming languages:

**JavaScript, Python, Dart, HTML, CSS, Java**

### ⚡ Code Execution
- Run code directly from the browser
- Real-time output generation
- Language-specific execution support

### 🔐 User Authentication
- User Registration
- User Login
- Secure Authentication
- Session Management

### 🖼️ Image to Text (OCR)
- Extract text from uploaded images
- Fast and accurate text recognition
- Easy copy and reuse functionality

### 🎙️ Voice to Text Converter
- Convert speech into text
- Real-time voice recognition
- Useful for notes, documentation, and coding assistance

### 🎨 Modern User Interface
- Responsive Design
- Interactive Dashboard
- Clean Navigation
- User-Friendly Experience

---

## 🛠️ Tech Stack

### Frontend
- React.js
- HTML5
- CSS3
- JavaScript

### Backend
- Node.js
- Express.js

### Database
- MongoDB

### Authentication
- JWT Authentication
- MongoDB User Management

### Additional Technologies
- OCR Integration
- Speech Recognition API
- REST APIs

---

## 📂 Project Structure

```bash
NovaCore-main
│
├── backend
│   ├── db
│   ├── model
│   ├── router
│   ├── app.js
│   └── package.json
│
├── frontend
│   ├── public
│   ├── src
│   │   ├── Components
│   │   ├── Screens
│   │   ├── Editor
│   │   └── assets
│   └── package.json
│
└── documentation


## ▶️ How to Run the Project

### Step 1: Clone the Repository

```bash
git clone <repository-url>
cd NovaCore-main
```

### Step 2: Configure Environment Variables

Create a `.env` file inside the backend directory and add the required MongoDB connection string and JWT secret.

```env
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key
```

### Step 3: Install Backend Dependencies

```bash
cd backend
npm install
```

### Step 4: Start Backend Server

```bash
npm start
```

Backend server will run on:

```bash
http://localhost:5000
```

### Step 5: Install Frontend Dependencies

Open a new terminal:

```bash
cd frontend
npm install
```

### Step 6: Start Frontend Application

```bash
npm start
```

Frontend will run on:

```bash
http://localhost:3000
```

### Step 7: Access NovaCore

Open your browser and visit:

```bash
http://localhost:3000
```

### Step 8: Use the Platform

- Register/Login to your account
- Select a programming language
- Write code in the editor
- Execute code and view output
- Upload images for OCR text extraction
- Convert speech into text using Voice-to-Text

---

## 🧪 Supported Languages

| Language | Execution Support |
|-----------|------------------|
| JavaScript | ✅ |
| Python | ✅ |
| Dart | ✅ |
| HTML | ✅ |
| CSS | ✅ |
| Java | ✅ |

