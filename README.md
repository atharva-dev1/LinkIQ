LinkIQ — AI LinkedIn Networking Assistant

LinkIQ is an intelligent Chrome Extension that automates LinkedIn connection management, categorizes professional contacts, generates AI-powered welcome messages, and provides networking analytics.

It works as a personal networking assistant inside your browser to help students, developers, and job seekers grow their professional network efficiently.


---

📌 Overview

Managing LinkedIn requests manually is repetitive and inefficient.

LinkIQ automates this workflow by:

Accepting relevant connection requests

Filtering profiles intelligently

Sending personalized welcome messages

Detecting recruiters automatically

Tracking networking statistics

Storing connection insights in database

Generating AI-based replies


Built using Chrome Extension APIs + Node.js + MongoDB + AI APIs


---

✨ Features

🔹 Core Features

Auto accept connection requests

Smart keyword-based filtering

Personalized welcome message sender

Recruiter detection system

Networking analytics dashboard



---

🔹 AI Networking Assistant

Automatically generates contextual responses like:

> Hi [Name], thanks for connecting!
I'm currently exploring software development opportunities and would love to stay connected.



Supports integration with:

OpenAI API

Gemini API



---

🔹 Smart Profile Categorization

Automatically classifies connections into:

Recruiter

Engineer

Founder

Student

HR

Manager



---

🔹 Analytics Dashboard

Displays:

Total accepted connections

Recruiters connected

Company insights

Category breakdown

Daily networking activity



---

🔹 Follow-Up Reminder Engine (Planned Feature)

Automatically reminds you to reconnect with important contacts after selected time intervals.


---

🧠 System Architecture

Chrome Extension
      ↓
Content Script Automation Engine
      ↓
LinkedIn DOM Interaction
      ↓
Node.js Backend API
      ↓
MongoDB Database
      ↓
AI Message Generator


---

🛠 Tech Stack

Frontend (Extension UI)

HTML

CSS

JavaScript

Chrome Extension API


Backend

Node.js

Express.js


Database

MongoDB

Mongoose


AI Integration

OpenAI API / Gemini API


Visualization (Future Upgrade)

D3.js



---

📂 Project Structure

LinkIQ/

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
└── README.md


---

⚙️ Installation Guide

Step 1 — Clone Repository

git clone https://github.com/your-username/LinkIQ.git
cd LinkIQ


---

Step 2 — Install Backend Dependencies

cd server
npm install


---

Step 3 — Run Backend Server

node index.js

Server runs at:

http://localhost:5000


---

Step 4 — Load Chrome Extension

Open Chrome:

chrome://extensions/

Then:

1. Enable Developer Mode


2. Click Load unpacked


3. Select the extension folder



Extension is now ready ✅


---

▶️ How to Use

1. Open LinkedIn


2. Navigate to My Network


3. Click LinkIQ extension icon


4. Press Accept Requests



The extension will:

filter relevant profiles

accept requests

send welcome messages

store connection data

update analytics automatically



---

📊 Example Use Cases

Students

Build strong professional networks faster

Developers

Connect with recruiters efficiently

Job Seekers

Track hiring contacts automatically

Founders

Organize business connections intelligently


---

🔐 Privacy & Responsible Use

LinkIQ:

runs locally inside browser

does not collect passwords

does not store credentials

avoids spam automation

follows safe productivity-assistant design principles



---

🚀 Future Improvements

Upcoming upgrades include:

Recruiter priority scoring

Company-based filtering

Graph-based network visualization

Resume matching assistant

AI conversation continuation engine

SaaS cloud dashboard version



---

🧪 Learning Outcomes

This project demonstrates:

Chrome extension development

DOM automation scripting

full-stack system design

REST API integration

MongoDB database usage

AI workflow automation

productivity tool engineering



---

👨‍💻 Author

Sanjay Sharma

BCA Student | Software Developer
Interested in:

Full-stack development

AI automation tools

Dev productivity systems

intelligent browser extensions



---

⭐ Support

If you found this useful:

Star ⭐ the repository
Fork 🍴 the project
Share 📢 with developers
