# ☁️ Weather App (API Based)

**Weather App** is a modern and easy-to-use Android application that provides real-time weather information using a weather API. The app allows users to check current weather conditions based on their location or searched city, with a clean UI and fast performance.

---

## 🚀 Features

* 🌍 Get current weather by city name
* 📍 Location-based weather updates
* 🌡️ Display temperature, humidity, and wind speed
* ☁️ Weather condition (Clear, Cloudy, Rain, etc.)
* 🔄 Real-time data using Weather API
* ⚡ Fast & lightweight
* 🎨 Simple and clean UI

---

## 🌐 API Used

* **Weather API** (e.g. OpenWeatherMap)
* REST API with JSON response

---

## 🛠 Tech Stack

* **Language:** Kotlin
* **API Handling:** Retrofit
* **Architecture:** MVVM
* **UI:** XML + Material Design
* **Minimum SDK:** Android 6.0 (API 23)

---

## 🧠 Architecture Overview

The app follows **MVVM (Model–View–ViewModel)** architecture:

* **Model** – API response data models
* **Repository** – Handles API calls
* **ViewModel** – Manages UI state
* **View** – Activities / Fragments

---

## 📂 Project Structure

```
weather_app
 ├── data
 │    ├── model
 │    └── api
 ├── repository
 ├── viewmodel
 └── ui
```

---

## 🔐 Permissions Used

* Internet – to fetch weather data
* Location (Optional) – for current location weather

---

## 📦 Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/weather-app.git
   ```
2. Open the project in **Android Studio**
3. Add your API key in `local.properties` or `Constants.kt`
4. Sync Gradle files
5. Run the app

---

## 🎯 Use Cases

* Daily weather updates
* Travel planning
* Outdoor activity planning
* Learning API integration in Android

---

## 🤝 Contributing

Contributions are welcome!

* Fork the repository
* Create a new branch
* Commit your changes
* Open a Pull Request

---


## 🙌 Author

**Awais**
Android App Developer

If you like this project, don’t forget to ⭐ star the repository!

---

## 📬 Feedback

For bugs, suggestions, or improvements, feel free to open an issue on GitHub.

Happy Coding! ☀️🌧️
