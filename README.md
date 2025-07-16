# 🌤️ **Weather Forecast App**

A modern, responsive **real-time weather forecasting web app** 🌦️ that provides weather data based on city names using the **OpenWeatherMap API**. Built with **Python Flask**, this app displays temperature, humidity, wind speed, pressure, and more in a beautiful UI. Ideal for learning Flask, APIs, and web development basics.

---

## 🌟 Key Features

- 📍 **Location-Based Weather** by city name
- 🕐 **Real-Time Data** using OpenWeatherMap API
- 🌡️ Displays:
  - Temperature
  - Feels like
  - Humidity
  - Pressure
  - Wind Speed
- 🌐 **Built using Flask + HTML/CSS**
- 🔄 Refreshes dynamically for updated results
- 📱 Mobile-responsive interface

---

## 🔍 How It Works

1. User enters a city name (e.g., Delhi, London, New York)
2. App sends a request to **OpenWeatherMap API**
3. API responds with weather data in JSON format
4. Flask renders the data on a responsive result page

---

## 🛠️ Tech Stack

| Tool            | Purpose                      |
|-----------------|------------------------------|
| Python 🐍        | Programming language          |
| Flask 🌐         | Backend web framework         |
| HTML/CSS 🖥️      | Frontend                     |
| OpenWeatherMap 🌍 | Real-time weather API         |
| Bootstrap 🎨     | Styling and responsiveness    |

---

## 📸 Screenshots

### 🌆 Home Page

> User enters city name

![Home Page](https://github.com/Kusam-Badyal88/weather-forecast-app/blob/master/static/screenshots/home.png?raw=true)

---

### 🌦️ Forecast Result Page

> Displays temperature, weather type, humidity, wind speed, pressure, etc.

![Result Page](https://github.com/Kusam-Badyal88/weather-forecast-app/blob/master/static/screenshots/result.png?raw=true)

---

## ⚙️ How to Run the Project Locally

```bash
git clone https://github.com/Kusam-Badyal88/weather-forecast-app.git
cd weather-forecast-app
pip install -r requirements.txt
python app.py
Then open your browser at:

cpp
Copy
Edit
http://127.0.0.1:5000
📂 Project Structure
arduino
Copy
Edit
weather-forecast-app/
├── static/
│   ├── style.css
│   └── screenshots/
│       ├── home.png
│       └── result.png
├── templates/
│   ├── index.html
│   └── result.html
├── app.py
├── requirements.txt
└── README.md
✨ Future Enhancements
📍 Auto-detect location using IP

🌐 Add multi-language support

📆 5-day weather forecast integration

📱 Convert to Android app using Kivy or React Native
