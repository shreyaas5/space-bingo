# **🌌 Space Bingo**

Interactive real-time multiplayer bingo game designed for events, workshops, and student society activities.

A browser-based game where participants receive unique bingo cards while a host controls the caller panel and verifies claims live.


## **🚀 Features**
	•	🎲 Unique card generation for each player
	•	🧑‍💼 Separate Host and Player modes
	•	📡 Real-time claim validation
	•	🧠 Automatic pattern detection
	•	📊 Validity checking of winning claims
	•	📱 Mobile-friendly interface
	•	🏫 Suitable for live events and workshops


## **🧩 Supported Patterns**

### Pattern	Description

  • Orbit -	All outer border cells  
  • Supernova	- Both diagonals  
  • Galaxy - Inner 4×4 square  
  • Dipper - 3×3 L-shape anywhere  
  • Constellation - Any full 3×3 block  


## **🖥️ How It Works**

### Player
	1.	Open the website
	2.	Enter your name
	3.	Mark called items
	4.	Claim a pattern

### Host
	1.	Enter host password
	2.	Tick announced items
	3.	Claims get verified automatically

## 🏗️ Tech Stack
	•	HTML5
	•	CSS3
	•	Vanilla JavaScript
	•	Firebase Firestore (real-time sync)

No frameworks — built fully from scratch.


## 📂 Project Structure

space-bingo/  
│── index.html  
│── logo.png (optional)  
│── README.md  


## ⚙️ Setup (Run Your Own Event)

### 1. Create Firebase Project

Go to → https://console.firebase.google.com
Create a Web App + Firestore Database

### 2. Replace Firebase Config

Inside index.html:

const firebaseConfig = {
  apiKey: "YOUR_API_KEY",
  authDomain: "YOUR_PROJECT.firebaseapp.com",
  projectId: "YOUR_PROJECT_ID",
  storageBucket: "YOUR_PROJECT.appspot.com",
  messagingSenderId: "YOUR_SENDER_ID",
  appId: "YOUR_APP_ID"
};

### 3. Set Host Password

const HOST_SECRET = "yourpassword";


## 🎯 Use Cases
	•	Technical society events
	•	Hackathons
	•	Icebreakers
	•	Workshops
	•	Class engagement activities
	•	Online community events



## 👨‍💻 Author

Shreyaas Sachdeva
GitHub: https://github.com/shreyaas5


## 📄 License

Free to use for educational and event purposes.


## ⭐ Learning Highlights

### This project demonstrates:
	•	DOM manipulation
	•	Event-driven UI
	•	Pattern detection algorithms
	•	Real-time synchronization
	•	Role-based system design (host vs player)
