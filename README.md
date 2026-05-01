# 🌐 SHARON — Temporary Real-Time Collaboration Platform

SHARON is a modern, minimal, session-based web application that enables users to **share files and text in real-time** without any login system.

It is designed for quick, temporary collaboration — lightweight, fast, and accessible across devices.

---

## 🚀 Live Application

👉 https://abi431.github.io/sharon/index.html

---

## ✨ Features

* 🔐 **Session-Based Access**

  * Create a session with a unique ID and password
  * No login required

* ⏳ **24-Hour Expiry**

  * Sessions automatically expire after 24 hours

* 🔄 **Real-Time Text Sync**

  * Live collaborative typing across devices

* 📁 **Instant File Sharing**

  * Upload files via drag & drop
  * Files appear instantly for all users in the session

* ⚡ **Multi-Device Support**

  * Join the same session from different devices

* 🎨 **Modern UI**

  * Dark theme with subtle gradients
  * Minimal and distraction-free design

---

## 🧠 How It Works

1. User creates a session
2. A **Session ID + Password** is generated
3. Another user joins using those credentials
4. Both users land in the same workspace
5. Text and files sync in real-time

---

## 🛠️ Tech Stack

### Frontend

* HTML, CSS, JavaScript
* Responsive UI with modern design principles

### Backend (Firebase)

* 🔄 **Firebase Realtime Database** — live text sync
* 📦 **Firebase Storage** — file uploads
* ☁️ Fully serverless (no backend server required)

---

## 📁 Project Structure

```id="2o6k5v"
sharon/
│── index.html       # Landing page
│── create.html      # Create session
│── join.html        # Join session
│── session.html     # Main workspace
│── README.md
```

---

## ⚙️ Setup Instructions

### 1. Clone / Download

Download the project or clone the repository.

---

### 2. Create Firebase Project

* Go to https://console.firebase.google.com
* Create a new project

---

### 3. Enable Services

* Enable **Realtime Database** (test mode)
* Enable **Storage** (test mode)

---

### 4. Get Firebase Config

From:
👉 Project Settings → Your Apps → Web App

Copy config and paste into:

* `create.html`
* `join.html`
* `session.html`

---

## ⚠️ Notes

* Firebase is currently in **test mode** (open access)
* Not intended for production without security rules
* File size limits depend on Firebase free tier

---

## 🔮 Future Improvements

* 🔒 Secure Firebase rules
* 📊 Upload progress indicator
* 👥 User presence (who’s online)
* 🔗 Shareable session link
* 🧹 Auto-clean expired sessions

---

## 📌 Status

✅ Fully functional
🚀 Real-time collaboration working
🌐 Deployed on GitHub Pages

---

## 👨‍💻 Author

Built by **Abi**
A minimal, practical tool designed for real-world usage.

---

## ⭐ If you like this project

Give it a ⭐ on GitHub and share it!
