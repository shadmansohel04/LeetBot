# 🤖 LeetBot Backend

The backend engine for **LeetBot**—the 1st place winner at Ignitian Hacks 2024. Built with **Python Flask**, **Flask-SocketIO**, and **Mistral AI**, it drives real-time multiplayer PvP game sessions and integrates directly with the **LeetCode GraphQL API**.

---

## 🛠️ Tech Stack

- **Framework:** Python Flask (v3.0.3)
- **Real-Time Communication:** Flask-SocketIO / python-socketio / eventlet
- **AI Integration:** Mistral AI Python SDK (`mistralai`)
- **API Integration:** LeetCode GraphQL API via `requests`
- **CORS & Utilities:** Flask-CORS, Beautiful Soup, Pandas

---

## ⚙️ Installation & Running

1. Navigate to the backend directory:
   ```bash
   cd LeetBot-BACKEND
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Run the development server:
   ```bash
   python app.py
   ```

---

## 📂 Project Structure

```text
LeetBot-BACKEND/
├── app.py                  # Main Flask application & Socket.io event handlers
├── requirements.txt        # Python package dependencies
├── controllers/            # Game calculations, bot name generators, and logic
│   └── calculations.py
├── static/                 # Stylesheets and static assets
│   └── css/
│       └── style.css
└── templates/              # HTML templates for server-rendered views
    ├── base.html
    ├── home.html
    ├── index.html
    └── room.html
```

---

## 🔗 Links

- **Live App:** [https://leetcodebot-gumy.onrender.com/](https://leetcodebot-gumy.onrender.com/)
- **Devpost:** [https://devpost.com/software/leetcode-robo](https://devpost.com/software/leetcode-robo?ref_content=my-projects-tab&ref_feature=my_projects)
