# AI Collaborative Travel Planner

Plan trips with friends and family — collaborate in real-time!

## Features
- **Real-Time Collaboration** — Work together on travel plans
- **Itinerary Planning** — Organize destinations, dates, and activities
- **Budget Tracking & Expense Sharing** — Keep spending transparent
- **Smart Travel Suggestions** — Discover popular destinations
- **User Authentication** — Login/Signup with Firebase Auth

## Tech Stack
- **Frontend**: React (Create React App), React Router, Leaflet Maps
- **Backend**: Node.js, Express, Firebase Admin SDK
- **Database**: Cloud Firestore
- **Auth**: Firebase Authentication
- **Deployment**: Vercel (frontend)

## Getting Started

### Frontend
```bash
cd frontend
npm install
npm start
```
Opens at [http://localhost:3000](http://localhost:3000)

### Backend
```bash
cd backend
npm install
node index.js
```
Runs on port 5000

## Deployment
This project is configured for **Vercel** deployment. Connect the GitHub repo to Vercel and it will automatically build and deploy the frontend.

## Project Structure
```
├── frontend/          # React frontend (CRA)
│   ├── public/
│   └── src/
│       ├── App.js
│       ├── LoginSignInPage.js
│       └── components/
│           ├── DashboardPage.js
│           └── AddTripForm.js
├── backend/           # Express API server
│   ├── index.js
│   └── firebase.js
├── vercel.json        # Vercel deployment config
└── README.md
```