# 🌍 Smart Local Tour Guide – Multi-Agent AI Travel Recommendation System

Smart Local Tour Guide is a multi-agent travel recommendation web application designed to help users discover nearby attractions, restaurants, local events, and navigation information based on their selected location.

The system combines multiple specialized agents into a single platform to provide useful location-based travel recommendations.

## ✨ Features

- 🔍 Search for nearby tourist attractions
- 🍽️ Restaurant recommendations
- 🗺️ Navigation and route information
- 🎉 Local event recommendations
- 📍 Location-based travel suggestions
- 🤖 Multi-agent architecture
- 🗺️ Interactive map-based interface
- 🌐 REST API integration
- 📱 Responsive React user interface

## 🤖 Multi-Agent Architecture

The system consists of multiple specialized agents:

### 1. Attraction Search Agent
Finds nearby tourist attractions based on the user's selected location.

### 2. Restaurant Recommendation Agent
Provides restaurant recommendations around the selected destination.

### 3. Navigation Agent
Provides navigation and route-related information between locations.

### 4. Event Recommendation Agent
Helps users discover relevant local events and activities.

## 🛠️ Technologies Used

### Frontend
- React.js
- Vite
- JavaScript
- HTML5
- CSS3

### Backend
- Python
- FastAPI
- REST APIs

### APIs & Services
- OpenStreetMap
- Nominatim API
- Overpass API

### Deployment
- Render – Backend
- Vercel – Frontend

## 📂 Project Structure

SmartLocalTourGuide-main/
│
├── Backend/
│   ├── agents/
│   │   └── navigation_agent.py
│   ├── main.py
│   └── requirements.txt
│
├── frontend/
│   ├── public/
│   ├── src/
│   │   ├── components/
│   │   ├── pages/
│   │   ├── services/
│   │   ├── App.jsx
│   │   └── main.jsx
│   ├── package.json
│   └── vite.config.js
│
├── landing-page/
│
├── .gitignore
└── README.md

## ⚙️ Installation and Setup

### 1. Clone the Repository

git clone https://github.com/Nunnasushma/smart-local-tour-guide.git

cd smart-local-tour-guide/SmartLocalTourGuide-main

### 2. Backend Setup

cd Backend

pip install -r requirements.txt

uvicorn main:app --reload

### 3. Frontend Setup

Open another terminal:

cd frontend

npm install

npm run dev

## 🌐 Backend Deployment

The backend is deployed using Render:

https://smart-local-tour-guide.onrender.com

## 🚀 Live Demo

Frontend Live Demo: Coming Soon

## 💻 GitHub Repository

https://github.com/Nunnasushma/smart-local-tour-guide

## 🎯 Project Objective

The objective of Smart Local Tour Guide is to simplify travel planning by integrating multiple travel-related services into a single platform.

Instead of searching separately for attractions, restaurants, navigation, and events, users can access these services through specialized agents within one application.

## 🔮 Future Enhancements

- Personalized recommendations based on user preferences
- Real-time weather information
- Advanced route optimization
- Hotel recommendations
- User accounts and saved trips
- AI-based itinerary generation
- Improved event discovery
- Multilingual support

## 👩‍💻 Author

**Nunna Sushma**

B.Tech – Computer Science & Engineering (AI & ML)
