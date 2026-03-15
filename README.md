🚗 Link My Trip

Link My Trip is a web-based platform that helps people travel together to the same destination and share trip costs.
The system connects users who are traveling along similar routes and allows them to create trips, find matching trips, and send join requests.

The goal of the platform is to reduce travel costs, reduce traffic congestion, and encourage ride sharing.

📌 Features
👤 User Management

User Registration

Secure Login using Firebase Authentication

Profile Management

🛣️ Trip Management

Create new trips

Edit or delete existing trips

View available trips in real time

🔍 Trip Matching

Filter trips based on source and destination

Real-time trip updates

Suggest best matching trips

🤝 Join Request System

Send join requests to trip owners

Trip owners can accept or reject requests

Communication options for coordination

🛡️ Admin Controls

Monitor user activity

Handle trip reports

Review system performance

🏗️ System Architecture

The application follows a cloud-based architecture using Firebase services.

Main components include:

Frontend: HTML, CSS, JavaScript

Authentication: Firebase Authentication

Database: Firebase Firestore

Real-time updates: Firebase Realtime Database

Storage: Firebase Cloud Storage

Backend Logic: Firebase Cloud Functions

⚙️ Technology Stack
Technology	Purpose
HTML	Structure of web pages
CSS	Styling and layout
JavaScript	Client-side functionality
Firebase Authentication	User login and security
Firebase Firestore	Database storage
Firebase Realtime Database	Live trip updates
Firebase Cloud Storage	File and image storage
Firebase Cloud Functions	Backend logic
📂 Project Structure

Link-My-Trip
│
├──> index.html
├──> login.html
├──> register.html
├──> dashboard.html
│
├──>css
│   └──> styles.css
│
├──> js
│   ├──> auth.js
│   ├──> trips.js
│   ├──> matching.js
│   └── requests.js
│
├──> firebase
│   └── firebase-config.js
│
└──> README.md
🔄 System Workflow
1️⃣ User Login


User enters credentials

Firebase verifies user details

If valid → Dashboard

If invalid → Error message

2️⃣ Trip Creation

User enters trip details

Data is validated

Stored in Firestore

Appears in trip list in real time

3️⃣ Trip Matching

System retrieves available trips

Filters based on source and destination

Displays matching trips dynamically

4️⃣ Join Request

User sends join request

Trip owner receives notification

Owner accepts or rejects request

🚀 Future Improvements

AI-based route optimization

Integrated payment system

In-app messaging system

Mobile application

Rating and review system for users

🌍 Use Cases

College students traveling together

Office commuters sharing rides

Long-distance travelers splitting costs

Event-based travel coordination

👨‍💻 Contributors

GROUP 12 

📜 License

This project is created for educational and research purposes.

# 🚗 Link My Trip

🌍 **Live Platform:**https://link-my-trip.web.app 
📂 **GitHub Repository:** https://github.com/ayushjayapraksahan/link-my-trip
