# ?? LeetBot Frontend

The retro 8-bit frontend for **LeetBot**—the 1st place winner at Ignitian Hacks 2024. Built with **React.js**, **Vite**, and styled with **NES.CSS**, it provides an arcade-style UI for multiplayer PvP LeetCode stat battles.

---

## ??? Tech Stack

- **Framework:** React.js with Vite
- **Styling:** NES.CSS (retro 8-bit CSS framework), custom pixel art CSS
- **Routing & State:** React hooks and component pages (`GamePage`, `dash`, `homepage`, `boostPage`, `starter`)

---

## ?? Installation & Running

1. Navigate to the frontend directory:
   ```bash
   cd LeetBot-FRONTEND
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Start the development server:
   ```bash
   npm run dev
   ```

---

## ?? Project Structure

```text
LeetBot-FRONTEND/
+-- public/                 # Pixel art sprites, GIFs, and background images
+-- src/
¦   +-- assets/             # Game data and assets
¦   +-- pages/              # Views (homepage, GamePage, dash, boostPage, starter)
¦   +-- styles/             # Retro arcade stylesheets (gamePage.css, homePage.css, pixelated.css, etc.)
¦   +-- App.jsx             # Root component and router
¦   +-- App.css
¦   +-- main.jsx            # Entry point
¦   +-- index.css
+-- package.json
+-- vite.config.js
```

---

## ?? Links

- **Live App:** [https://leetcodebot-gumy.onrender.com/](https://leetcodebot-gumy.onrender.com/)
- **Devpost:** [https://devpost.com/software/leetcode-robo](https://devpost.com/software/leetcode-robo?ref_content=my-projects-tab&ref_feature=my_projects)
