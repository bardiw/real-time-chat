# 💬 Real-time-Chat App (Flask + SocketIO)

A minimal real-time chat application built using **Flask**, **Flask-SocketIO**, and **HTML/CSS/JS**. The app allows users to **register**, **log in**, and **chat live** with others in real time using WebSockets.

---

## ⚙️ Features

- 🔐 User registration and login with password hashing
- 🗨️ Real-time message broadcasting (Socket.IO)
- 📡 Lightweight Flask backend
- 🌐 Persian RTL UI
- 🚪 Logout and session management
- 📱 Responsive and simple UI (custom HTML/CSS)

---

## 📁 Project Structure

realtime-chat/
│
├── app.py # Main Flask application
├── templates/
│ ├── index.html # Chat interface
│ └── register.html # User registration page
├── static/ # (optional) CSS or JS files if separated
└── README.md # You're here!

---


## 🔧 Installation

1. 📥 Clone the repo:

```bash
git clone https://github.com/your-username/realtime-chat.git
cd realtime-chat
```

2. ▶️ Run the app:
```
python app.py
```

3.   🖥️ Open your browser and go to:
```
http://127.0.0.1:5000/
```

---

## 📋 Requirements
- Python 3.7+

- Flask

- Flask-SocketIO

- Werkzeug (comes with Flask)

📌 requirements.txt:
```
Flask
Flask-SocketIO
```

---

## 🌐 Pages Overview
/register: Sign up with username and password (hashed with Werkzeug)

/login: Log in securely

/: Main chatroom (if logged in)

/logout: Ends user session

---

## 🔒 Notes
- For simplicity, user data is stored in memory (dictionary) — not persistent.

- Do not use this in production without adding:

- Database (e.g. SQLite, PostgreSQL)

- Input validation

- CSRF protection

- Session timeout management

---

##🧑‍💻 Author    
 Bardia Javadi    
 Computer Engineering student   
 GitHub: @bardiw
