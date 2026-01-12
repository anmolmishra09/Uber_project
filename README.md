# Uber_project
🚖 Uber Clone – Ride Booking Web Application

A full-stack Uber Clone web application that allows users to book rides, view nearby drivers, estimate fares, and track rides in real time. This project focuses on building a scalable, user-friendly ride-hailing platform using modern web technologies.

🔹 Features

🔐 User Authentication (Login / Signup)

📍 Real-time Location Selection (Pickup & Drop)

🚗 Ride Booking System

💰 Fare Estimation based on distance

🗺️ Interactive Maps Integration

📱 Responsive UI (Mobile & Desktop)

🧑‍✈️ Driver & Rider Flow (Basic)

⚡ Smooth UI/UX with modern design

🔹 Tech Stack

Frontend

React.js

Tailwind CSS

JavaScript (ES6)

Vite

Backend (if applicable)

Node.js

Express.js

MongoDB

REST APIs

Other Tools

Git & GitHub

Map API (Google Maps / Mapbox)

Axios

🔹 Project Structure
Uber_project/
│
├── .gitignore
│
├── Backend/
│   ├── app.js
│   ├── package.json
│   ├── package-lock.json
│   │
│   ├── controllers/
│   │   ├── captain.controller.js
│   │   ├── map.controller.js
│   │   ├── ride.controller.js
│   │   └── user.controller.js
│   │
│   ├── db/
│   │   └── db.js
│   │
│   ├── middlewares/
│   │   └── auth.middleware.js
│   │
│   └── models/
│       ├── blacklistToken.model.js
│       ├── captain.model.js
│       ├── ride.model.js
│       └── user.model.js
│
├── frontend/
│   ├── index.html
│   ├── package.json
│   ├── package-lock.json
│   ├── eslint.config.js
│   ├── postcss.config.js
│   ├── README.md
│   │
│   ├── public/
│   │   └── vite.svg
│   │
│   └── src/
│       ├── App.jsx
│       ├── App.css
│       │
│       ├── assets/
│       │   └── react.svg
│       │
│       └── components/
│           ├── CaptainDetails.jsx
│           ├── ConfirmRide.jsx
│           ├── ConfirmRidePopUp.jsx
│           ├── FinishRide.jsx
│           ├── LiveTracking.jsx
│           └── LocationSearchPanel.jsx


🔹 How to Run Locally
# Clone the repository
git clone https://github.com/anmolmishra09/Uber_project

# Navigate to project folder
cd Uber_project

# Install dependencies
npm install

# Start development server
npm run dev

🔹 Screenshots

(Add screenshots of your app UI here)

🔹 Learning Outcomes

Hands-on experience with React component architecture

Implemented real-world app logic

Improved understanding of state management

API integration & async handling

UI/UX design for scalable applications

🔹 Future Enhancements

🚀 Real-time driver tracking

💳 Payment gateway integration

🔔 Push notifications

🧠 AI-based route optimization

📊 Admin dashboard

🔹 Author

👤 Anmol Mishra
🎓 B.Tech CSE | Frontend / Software Engineer Intern
