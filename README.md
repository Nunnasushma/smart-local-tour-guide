# 🌍 Smart Local Tour Guide

**Smart Local Tour Guide** is a multi-agent travel recommendation web application designed to help users discover nearby tourist attractions, restaurants, local events, and navigation information based on their selected location.

The system combines multiple specialized agents into a single platform, making local travel planning easier and more convenient.

## 🚀 Live Demo

🌐 **Live Application:** https://smart-local-tour-guide-eta.vercel.app/

⚙️ **Backend API:** https://smart-local-tour-guide.onrender.com

💻 **GitHub Repository:** https://github.com/Nunnasushma/smart-local-tour-guide

---

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

---

## 🤖 Multi-Agent Architecture

The Smart Local Tour Guide uses multiple specialized agents to handle different travel-related tasks.

### 1. 🔍 Attraction Search Agent

The Attraction Search Agent helps users discover nearby tourist attractions based on their selected city or location.

It uses location information and APIs such as OpenStreetMap, Nominatim, and Overpass to retrieve nearby places.

### 2. 🍽️ Restaurant Recommendation Agent

The Restaurant Agent provides restaurant recommendations around the user's selected destination.

It helps travelers quickly discover nearby dining options without searching separately on different platforms.

### 3. 🗺️ Navigation Agent

The Navigation Agent provides route and navigation-related information between locations.

It helps users understand how to reach their selected destination.

### 4. 🎉 Event Recommendation Agent

The Event Recommendation Agent helps users discover local events and activities around their selected destination.

---

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
- Uvicorn

### APIs & Services

- OpenStreetMap
- Nominatim API
- Overpass API

### Deployment

- **Frontend:** Vercel
- **Backend:** Render
- **Version Control:** Git & GitHub

---

## 📂 Project Structure

```text
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
│   │   ├── assets/
│   │   ├── components/
│   │   │   ├── AttractionCard.jsx
│   │   │   ├── EventCard.jsx
│   │   │   ├── MapView.jsx
│   │   │   ├── Navbar.jsx
│   │   │   ├── RestaurantCard.jsx
│   │   │   ├── RouteInfoCard.jsx
│   │   │   ├── SearchBar.jsx
│   │   │   ├── Sidebar.jsx
│   │   │   └── SimulationWidget.jsx
│   │   │
│   │   ├── pages/
│   │   │   ├── Dashboard.jsx
│   │   │   └── LandingPage.jsx
│   │   │
│   │   ├── services/
│   │   │   └── api.js
│   │   │
│   │   ├── App.jsx
│   │   └── main.jsx
│   │
│   ├── package.json
│   └── vite.config.js
│
├── landing-page/
│   ├── assets/
│   ├── index.html
│   ├── script.js
│   └── style.css
│
├── .gitignore
└── README.md
```

---

## ⚙️ Installation and Setup

### 1. Clone the Repository

```bash
git clone https://github.com/Nunnasushma/smart-local-tour-guide.git
```

Navigate to the project:

```bash
cd smart-local-tour-guide/SmartLocalTourGuide-main
```

---

## 🐍 Backend Setup

Navigate to the backend:

```bash
cd Backend
```

Install the Python dependencies:

```bash
pip install -r requirements.txt
```

Start the FastAPI backend:

```bash
uvicorn main:app --reload
```

The backend will normally run locally at:

```text
http://127.0.0.1:8000
```

---

## ⚛️ Frontend Setup

Open another terminal and navigate to the frontend:

```bash
cd frontend
```

Install dependencies:

```bash
npm install
```

Start the development server:

```bash
npm run dev
```

Open the URL displayed by Vite in your browser.

---

## 🔄 Application Workflow

```text
User
  ↓
React Frontend
  ↓
User enters/selects location
  ↓
FastAPI Backend
  ↓
Multi-Agent System
  ↓
├── Attraction Search Agent
├── Restaurant Recommendation Agent
├── Navigation Agent
└── Event Recommendation Agent
  ↓
External APIs / Location Services
  ↓
Results displayed to user
```

---

## 🎯 Project Objective

The objective of the **Smart Local Tour Guide** is to simplify local travel planning by integrating multiple travel-related services into a single application.

Instead of using different platforms to search for attractions, restaurants, navigation, and events, the system provides these services through specialized agents within one interface.

---

## 🌐 Deployment

### Frontend

The React/Vite frontend is deployed using **Vercel**.

**Live Demo:**  
https://smart-local-tour-guide-eta.vercel.app/

### Backend

The FastAPI backend is deployed using **Render**.

**Backend API:**  
https://smart-local-tour-guide.onrender.com

---

## 🔮 Future Enhancements

- Personalized recommendations based on user interests
- AI-generated travel itineraries
- Hotel recommendations
- Real-time weather information
- Advanced route optimization
- User authentication
- Save favorite destinations
- Trip history
- Improved event discovery
- Multilingual support
- More advanced AI-based recommendations

---

## 💡 Use Cases

The application can be useful for:

- Tourists exploring an unfamiliar city
- Travelers looking for nearby attractions
- Users searching for restaurants around a destination
- Finding local activities and events
- Planning routes between tourist locations
- Creating a simple local travel plan

---

## 👩‍💻 Author

**Nunna Sushma**

B.Tech – Computer Science & Engineering (AI & ML)

---

## ⭐ Support

If you find this project useful, consider giving the repository a ⭐ on GitHub.

**Repository:**  
https://github.com/Nunnasushma/smart-local-tour-guide
