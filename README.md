🚀 LinkedIn Smart Networking Assistant

An intelligent Chrome Extension + Full-Stack Automation Tool that helps manage LinkedIn connection requests, categorize professional contacts, generate AI-powered replies, and analyze networking growth.

Designed as a productivity assistant for modern developers and job seekers, this tool automates repetitive networking workflows while keeping interactions personalized and meaningful.


---

📌 Project Overview

Managing LinkedIn connections manually can be time-consuming and inefficient.

This project solves that problem by providing:

✅ Auto connection request handling
✅ Smart profile filtering
✅ AI-generated welcome messages
✅ Recruiter detection system
✅ Networking analytics dashboard
✅ Follow-up reminder automation
✅ Connection categorization engine
✅ MongoDB-based connection tracking

The extension acts as a personal LinkedIn networking assistant inside your browser.


---

✨ Features

🔹 Core Features

Auto accept connection requests

Filter connections using keywords

Send personalized welcome messages

Track accepted connections

View networking analytics dashboard



---

🔹 Smart Filtering System

Automatically detects:

Recruiters

Engineers

Founders

Students

HR professionals

Managers


Accepts only relevant profiles based on rules.


---

🔹 AI Message Generator

Generates personalized replies like:

> Hi [Name], thanks for connecting!
I'm currently exploring software development opportunities and would love to stay in touch.



Powered by modern LLM APIs.


---

🔹 Connection Analytics Dashboard

Displays:

Total connections accepted

Recruiters connected

Companies discovered

Daily networking stats

Category-wise breakdown



---

🔹 Follow-Up Reminder Engine

Automatically reminds you to reconnect with:

recruiters

hiring managers

collaborators


after selected time intervals.


---

🔹 Database Storage (MongoDB)

Stores structured connection data:

Name

Headline

Company

Category

Date added


Enables long-term networking insights.


---

🧠 System Architecture

Chrome Extension
      ↓
Content Script Automation Engine
      ↓
LinkedIn DOM Interaction Layer
      ↓
Node.js Backend API
      ↓
MongoDB Database
      ↓
AI Message Generator
      ↓
Analytics Dashboard


---

🛠️ Tech Stack

Frontend (Extension UI)

HTML

CSS

JavaScript

Chrome Extension API


Automation Layer

DOM scripting

Content scripts

Event triggers


Backend

Node.js

Express.js


Database

MongoDB

Mongoose


AI Integration

OpenAI API / Gemini API


Visualization (Advanced Feature)

D3.js



---

📂 Project Structure

linkedin-smart-assistant/

│
├── extension/
│   ├── manifest.json
│   ├── popup.html
│   ├── popup.js
│   ├── content.js
│   └── background.js
│
├── server/
│   ├── index.js
│   ├── routes/
│   └── models/
│
├── database/
│
└── README.md


---

⚙️ Installation Guide

Step 1 — Clone Repository

git clone https://github.com/your-username/linkedin-smart-assistant.git
cd linkedin-smart-assistant


---

Step 2 — Install Backend Dependencies

cd server
npm install


---

Step 3 — Run Backend Server

node index.js

Server runs on:

http://localhost:5000


---

Step 4 — Load Chrome Extension

Open:

chrome://extensions/

Then:

1. Enable Developer Mode


2. Click Load unpacked


3. Select /extension folder



Extension is now active ✅


---

▶️ How to Use

1. Open LinkedIn


2. Navigate to My Network


3. Click extension icon


4. Press Accept Requests


5. Tool will:

filter profiles

accept connections

send welcome message

store connection data

update analytics





---

📊 Example Use Cases

This tool helps:

Students

Build stronger professional networks faster

Developers

Connect with recruiters efficiently

Job Seekers

Track hiring contacts automatically

Founders

Organize business connections


---

🔐 Privacy & Safety

This tool:

runs locally in browser

does not collect passwords

does not store credentials

avoids mass-spam automation

focuses on productivity assistance


Built with responsible automation principles.


---

🚀 Future Improvements

Upcoming upgrades:

Smart recruiter scoring system

Company-based filtering

Network strength prediction

Resume matching assistant

AI conversation continuation engine

Graph-based connection visualization

SaaS deployment version



---

🧪 Learning Outcomes

This project demonstrates:

✔ Chrome extension development
✔ DOM automation scripting
✔ full-stack architecture design
✔ REST API integration
✔ MongoDB data modeling
✔ AI-powered workflow automation
✔ real-world productivity tooling


---

👨‍💻 Author

Sanjay Sharma

BCA Student | Software Developer
Interested in:

Full-stack development

AI automation systems

Dev tools engineering

Productivity platforms



---

⭐ Support the Project

If you found this useful:

⭐ Star the repository
🍴 Fork the project
📢 Share with developers

It helps the project grow and improves visibility.
