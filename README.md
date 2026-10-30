# 🤖 LeetBot

<div align="center">

🏆 **1st Place Winner at Ignitian Hacks 2024** 🏆

[![Live Demo](https://img.shields.io/badge/Live-Demo-brightgreen?style=for-the-badge&logo=render)](https://leetcodebot-gumy.onrender.com/)
[![Devpost](https://img.shields.io/badge/Devpost-Project-blue?style=for-the-badge&logo=devpost)](https://devpost.com/software/leetcode-robo?ref_content=my-projects-tab&ref_feature=my_projects)
[![Python Flask](https://img.shields.io/badge/Backend-Python%20Flask-orange?style=for-the-badge&logo=flask)](./LeetBot-BACKEND)
[![React.js](https://img.shields.io/badge/Frontend-React.js-blue?style=for-the-badge&logo=react)](./LeetBot-FRONTEND)
[![NES.css](https://img.shields.io/badge/Style-NES.css-yellow?style=for-the-badge)](https://nostalgic-css.github.io/NES.css/)

</div>

---

## 🌟 Overview

**LeetBot** is an immersive multiplayer PvP battle game powered by players' **LeetCode stats**! Built during **Ignitian Hacks 2024** where it proudly secured **1st Place**, LeetBot transforms competitive programming metrics into epic turn-based combat. 

Players enter their LeetCode usernames, harness the **Mistral AI API** to generate unique battle bot identities, and fetch real-time player performance stats via the **LeetCode GraphQL API**. Post-hackathon refinements have brought LeetBot to life on the web—grab a friend and challenge them to a match!

---

## 🔗 Links

- **Live Application:** [https://leetcodebot-gumy.onrender.com/](https://leetcodebot-gumy.onrender.com/)
- **Devpost Submission:** [https://devpost.com/software/leetcode-robo](https://devpost.com/software/leetcode-robo?ref_content=my-projects-tab&ref_feature=my_projects)

---

## 🏗️ Project Architecture

LeetBot is split into two main components:
1. **[LeetBot-BACKEND](./LeetBot-BACKEND)**: A Python Flask & Flask-SocketIO server handling real-time WebSocket communication, game calculation logic, Mistral AI integration, and LeetCode GraphQL API queries.
2. **[LeetBot-FRONTEND](./LeetBot-FRONTEND)**: A React.js single-page application styled in retro 8-bit fashion using `NES.css`, managing player lobbies, dashboards, and live combat rooms.

---

## 🚀 Quick Start

### Prerequisites
- Python 3.10+
- Node.js & npm

### 1. Run the Backend
```bash
cd LeetBot-BACKEND
pip install -r requirements.txt
python app.py
```

### 2. Run the Frontend
```bash
cd LeetBot-FRONTEND
npm install
npm run dev
```

---

## 📄 License

Distributed under the MIT License. See project files for details.
