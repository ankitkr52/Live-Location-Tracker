# Live Location Tracker

A simple real-time location sharing web application. Generate a shareable link and track someone's live location instantly using Socket.io.

---

## ✨ Features

- Simple login system
- Shareable link generation for location tracking
- Real-time location updates (powered by Socket.io)
- Receiver doesn't need to login
- Mobile responsive design
- Cloudflared support for public URL

---

## 🚀 How It Works

1. Sender login karta hai (Default: `admin` / `admin`)
2. Sender ko ek unique shareable link milta hai
3. Sender us link ko receiver/target ko bhejta hai
4. Receiver link open karta hai aur location permission deta hai
5. Receiver ki live location sender ke dashboard par real-time mein dikhne lagti hai

---

## 🛠️ Installation & Setup

### 1. Project Clone karo
```bash
git clone https://github.com/ankitkr52/Live-Location-Tracker.git
cd Live-Location-Tracker
2. Dependencies Install karo
Bashnpm install
3. Server Start karo
Bash# Development
npm run dev

# Production
npm start
Server normally http://localhost:6589 par chalega.

🔑 Default Login

Username: admin
Password: admin


🌐 Public URL (Cloudflared)
Server start karne ke baad automatically ek public URL generate ho jayega. Console mein check karo.

📁 Project Structure
textLive-Location-Tracker/
├── public/             # Frontend (HTML, CSS, JS)
├── views/              # HTML templates
├── router/             # Express routes
├── config.js           # Port, credentials
├── server.js           # Main server file
├── package.json
├── README.md
└── .gitignore
