# 🥫 Pantry Tracker – Headstarter Fellowship 2025

Pantry Tracker is a streamlined inventory management system built during the Headstarter Software Engineering Fellowship (Summer 2025). Designed to help users track, add, update, and monitor pantry items efficiently, it showcases clean architecture, modular design, and scalable code practices.

---

## 🚀 Project Highlights

- 🔄 **Track & Update Items:** Add, edit, or delete pantry items with seamless UI interactions.
- 🧠 **Fellowship-Built:** Developed as part of a structured full-stack engineering curriculum focused on scalable architecture, clean code, and collaborative workflows.
- ⚙️ **Modular Codebase:** Organized backend and frontend logic for easy expansion and testing.
- 🧪 **Test-Driven Development:** Includes unit and integration tests to ensure feature reliability.

---

## 🛠️ Tech Stack

- **Frontend:** HTML5, CSS3, JavaScript
- **Backend:** Node.js, Express.js
- **Database:** MongoDB (Mongoose)
- **Version Control:** Git + GitHub
- **Deployment:** (Optional) Can be deployed via Heroku, Render, or Vercel

---

## 🧩 Features

- ✅ Add pantry items with quantity and category
- ♻️ Update and delete items easily
- 📦 Categorize items by type (e.g., canned, grains, refrigerated)
- 📊 Option to expand into stats, expiry reminders, or low-stock alerts

---

## 📂 Folder Structure

```
pantry-tracker/
├── client/ # Frontend code
├── server/ # Express backend
│ ├── routes/ # API endpoints
│ └── models/ # Mongoose models
├── .env # Environment variables
├── README.md
└── package.json
```

---

## 🧪 How to Run Locally

```bash
# Clone the repo
git clone https://github.com/bshongwe/headstarter_pantry-tracker.git
cd headstarter_pantry-tracker

# Install backend dependencies
npm install

# (Optional) Set up .env for MongoDB connection
touch .env
echo "MONGO_URI=your_mongodb_connection_string" >> .env

# Run the server
npm start

