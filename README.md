
# 🌦️ Weather App

A simple **Weather App** built with **Spring Boot** and **WeatherAPI** that provides real-time weather information and a 3-day forecast.  
The app has a **REST API backend** and a **responsive frontend** built with HTML, CSS, and JavaScript.

---

## ✨ Features
- Fetch current weather by city.
- 3-day weather forecast (limited by free WeatherAPI plan).
- Clean REST API endpoints built with Spring Boot.
- Responsive UI with search and forecast cards.
- JSON to POJO mapping with DTOs for clean responses.
- Configurable API key and base URLs via `application.properties`.

---

## 🛠️ Tech Stack
**Backend:**
- Java 17, Spring Boot, Spring Web
- RestTemplate for external API calls
- Maven build tool
- DTO/POJO mapping with Jackson

**Frontend:**
- HTML5, CSS3, JavaScript (Fetch API)

**Tools:**
- IntelliJ IDEA
- Postman
- WeatherAPI (external data provider)

---

## 🔮 Future Improvements

* Add caching to reduce API calls.
* Implement error handling and better UI notifications.
* Deploy to cloud (Heroku/Render).
* Switch from RestTemplate to WebClient (reactive).

---

