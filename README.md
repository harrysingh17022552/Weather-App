# 🌦️ Weather App

A modern, responsive weather application that provides real-time weather updates, dynamic UI changes, and enhanced user experience with features like recent searches, location-based weather, and custom alerts.

---

## 🚀 Features

### 🌍 Core Functionality

* Fetch real-time weather data using API
* Display current weather conditions based on:

  * 📍 User’s current location (latitude & longitude)
  * 🔍 Searched city (India-focused support)
* 4-day weather forecast with clickable UI interaction

---

### 🎨 UI & UX Enhancements

* Dynamic background based on weather conditions
* Inverted heading color fix for better visibility
* Fixed height for recent search dropdown
* Clean and responsive UI built with Tailwind CSS
* Custom weather-based GIFs for visual experience

---

### ⚡ Smart Features

* 🔥 Hot temperature alerts (custom extreme weather warnings)
* 📌 Recent search dropdown:

  * Stores searched cities in **state + session storage**
  * Quick access to previously searched locations
* 🌐 Separate handling for:

  * Current location weather
  * Searched location weather

---

### 🛡️ Error Handling

* Handles all API-side errors gracefully
* Prevents empty search input submission
* Improved reliability with fallback UI behavior

---

### 🔄 Persistence & Optimization

* Session storage integration for recent searches
* Auto-fetch weather on page reload based on user location

---

## 🛠️ Tech Stack

```
next.js, javascript, tailwind css, weather api, session storage
```

---

## 📌 Key Implementation Highlights

* **State Management** for storing and distributing API data
* **Component-based architecture** using reusable UI blocks
* **Higher Order Functions** to structure data flow
* **Dynamic rendering** for forecast interaction
* **Session-based persistence** for improved UX

---

## 📸 Screens & Experience

* Real-time weather dashboard
* Interactive forecast cards
* Smart recent search suggestions
* Dynamic UI adapting to weather conditions

---

## 🧠 Learnings

* Handling real-world API edge cases
* Managing UI state with persistence
* Enhancing UX with small but impactful features
* Structuring scalable frontend architecture

---

## 🔮 Future Improvements

* Global search support (not limited to India)
* Add hourly forecast
* Dark/light mode toggle
* PWA support
* Better animations & transitions

---

## 📄 License

This project is open-source and available under the MIT License.

---

## 👨‍💻 Author

**Harish Nigam**

---

⭐ If you like this project, consider giving it a star!
