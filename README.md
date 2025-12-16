## 🏓 ft_transcendence – 42 School

### 🏆 Score: **125/100**

## 👥 Group Project

This project was completed in collaboration with **[sergii-moroz](https://github.com/sergii-moroz), [oliferovych](https://github.com/oliferovych), [alex-anokhin](https://github.com/alex-anokhin), [Sergii](https://github.com/SterneStehen)**

## 📚 About the Project

**ft_transcendence** is the final major project in the 42 School core curriculum focused on **modern web development**. The goal is to create a **real-time, interactive multiplayer web application** built around a refined version of the classic **Pong** game.

Beyond gameplay, this project emphasizes **secure authentication, real-time communication, data persistence, and rich front-end experience**. Users can compete remotely, chat live, view statistics, and interact with a secure, full-stack platform.

## 🧩 Implemented Modules

### 🌐 Web & Architecture

1. **Backend Framework (Major Module)**
   Built the backend API using **Fastify** (Node.js framework), focusing on performance, modularity, and HTTP + WebSocket support.

2. **Frontend Toolkit (Minor Module)**
   Developed a responsive **Single-Page Application (SPA)** frontend using only **TypeScript** and Tailwind CSS

3. **Database Integration (Minor Module)**
   Used **SQLite** for backend persistence, storing users, matches, 2FA settings, and game statistics.

### 👤 User Management & Security

4. **Standard User Management (Major Module)**
   Users can register, log in, and maintain persistent profiles across tournaments and sessions.

5. **Two-Factor Authentication & JWT (Major Module)**
   Added **JWT authentication** and **Two-Factor Authentication** to secure user accounts and protect API endpoints.

### 🎮 Gameplay & Real-Time Features

6. **Server-Side Pong & API (Major Module)**
   Implemented the Pong game logic on the backend, providing a synchronized API and real-time state updates via WebSocket.

7. **Remote Players (Major Module)**
   Enabled true online multiplayer, allowing players on different devices to join and play in the same match.

8. **Live Chat (Major Module)**
   Built a real-time chat feature that lets users communicate inside the app.

9. **AI Opponent (Major Module)**
   Developed an **AI Pong opponent**, providing an engaging single-player experience.

### 📊 UX Improvements & Compatibility

10. **User & Game Stats Dashboards (Minor Module)**
    Added dashboards showing player performance, match history, and win/loss rates.

11. **Advanced 3D Techniques (Major Module)**
    Employed **3D rendering** for enhanced visuals beyond classic 2D gameplay.

12. **Support on All Devices (Minor Module)**
    Ensured broad support for desktops, tablets, and mobile screens.

13. **Expanded Browser Compatibility (Minor Module)**
    Tested and optimized across multiple modern browsers.

## 📚 What I Learned

* **Full-Stack Web Development** — Designed and implemented a structured backend with Fastify and a responsive SPA frontend from the ground up without any framworks just typescript .
* **Real-Time Communication** — Built socket-driven features for gameplay and live chat.
* **Authentication & Security** — Applied secure practices with JWT, 2FA, and token management.
* **Database Design & Persistence** — Used SQLite for storing user and game data.
* **Collaboration & Planning** — Worked in a larger team to coordinate building, testing, and integrating features.

## 🚀 Usage

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/t-ecker/42-transcendence.git
cd 42-transcendence
```

### 2️⃣ Set Up Environment

```bash
# Install dependencies
npm install

# Generate environment variables
bash env_gen.sh
# Then edit `.env` with your secrets
```

### 3️⃣ Build & Run

```bash
npm run build
npm run dev
```

### 4️⃣ Open in Browser

```text
http://localhost:<PORT>
```

## 🏁 Conclusion

**ft_transcendence** serves as a demonstration of modern web engineering — combining secure authentication, real-time gameplay, responsive interfaces, and persistent user data.
