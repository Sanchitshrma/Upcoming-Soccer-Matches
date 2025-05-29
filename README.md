# SportsOrca

A dynamic web application to display upcoming soccer matches! ⚽

---

## 🚀 Overview

**SportsOrca** is a web application that:

- Fetches and displays a list of upcoming soccer matches.
- Uses a Node.js + Express backend serving a mock API (`/api/matches`).
- A simple HTML + JavaScript frontend that consumes the API and shows match details dynamically.

---

## ✨ Features

✅ **Upcoming Matches:**  
Shows teams, match date, venue, and competition name.

✅ **Mock API with Express:**  
No need for real API keys during development – all data is mocked!

✅ **CORS-enabled Backend:**  
Smooth frontend-backend communication without CORS issues.

✅ **Modern & Clean Code:**  
Frontend and backend separated for better maintainability.

---

## 📁 Project Structure
```
SportsOrca/
├── .gitignore
├── index.html
├── package.json
├── server.js
└── …
```
---

## 💻 Installation & Setup

1️⃣ **Clone the repository:**

```bash
git clone https://github.com/Sanchitsharma/Upcoming-Soccer-Matches.git
cd Upcoming-Soccer-Matches
```
2️⃣ Install dependencies
```
npm install
```
3️⃣ Start server
```
node server.js
```
The backend will be live at http://localhost:3000/api/matches.

4️⃣ Open the frontend:
	•	Open index.html directly in your browser.
or
	•	Use a local dev server like live-server, vite, or http-server for better experience.

 🔥 API Endpoint
	•	GET /api/matches
Returns JSON data of upcoming soccer matches:
```
{
  "matches": [
    {
      "id": 1,
      "homeTeam": { "name": "Manchester City", "shortName": "MCI" },
      "awayTeam": { "name": "Arsenal", "shortName": "ARS" },
      "utcDate": "2025-06-01T18:00:00Z",
      "competition": { "name": "Premier League" },
      "status": "SCHEDULED",
      "venue": "Etihad Stadium"
    },
    ...
  ]
}
```

🛠️ Frontend Integration

In index.html, the frontend script:
	•	Calls http://localhost:3000/api/matches using fetch.
	•	Dynamically populates the page with match data.

⸻

📝 Scripts
	•	node server.js – Start the backend server.

⸻

⚙️ Tech Stack
	•	Backend: Node.js, Express.js
	•	Frontend: HTML, CSS, JavaScript (vanilla)

⸻

🤝 Contributing

Pull requests are welcome!
For major changes, please open an issue first to discuss what you would like to change.
