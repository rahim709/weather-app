# 🌦️ Weather App

A simple and responsive **Weather Application** built using **HTML, CSS, and JavaScript** that allows users to check real-time weather information either by granting location access or by searching for a city.

🔗 **Live Demo:** https://weathergrid.netlify.app/

---

## 🚀 Features

- 🌍 **Your Weather**
  - Fetches real-time weather data using the user's current location
  - Uses browser **Geolocation API**
- 🔎 **Search Weather**
  - Search weather details by city name
- 📊 **Displays:**
  - Temperature (°C)
  - Weather description & icon
  - Wind speed
  - Humidity
  - Cloudiness
- ⚠️ Error handling for invalid city names
- ⏳ Loading indicator while fetching data
- 📱 Fully responsive design

---

## 🛠️ Tech Stack

- **HTML5**
- **CSS3**
- **JavaScript**
- **OpenWeatherMap API**

---

## 📁 Project Structure

```
.
├── index.html
├── style.css
├── script.js
├── assets/
│   ├── cloud.png
│   ├── humidity.png
│   ├── wind.png
│   ├── location.png
│   ├── loading.gif
│   ├── not-found.png
│   └── temperature_logo.png
└── README.md
```

---

## 🔑 API Used

- **OpenWeatherMap API**
  - Endpoint: `https://api.openweathermap.org/data/2.5/weather`
  - Units: Metric

> ⚠️ Make sure to replace the API key in `script.js` with your own key if you fork this project.

```js
const API_KEY = "YOUR_API_KEY_HERE";
```

---

## 🧠 How It Works

1. On page load, the app checks sessionStorage for saved user coordinates.
2. If not found, it asks for location permission.
3. Weather data is fetched using latitude & longitude or city name.
4. UI updates dynamically based on API response.
5. Errors (like invalid city) are handled gracefully.

---

## 📸 Screens Included

- Grant Location Access screen
- Search Weather screen
- Weather Info Display
- City Not Found Error screen

---

## 🧪 How to Run Locally

1. **Get your API Key:**
   - Visit [OpenWeatherMap](https://openweathermap.org/api)
   - Sign up for a free account
   - Go to API Keys section and generate a new key

2. **Clone the repository:**

3. **Add your API Key:**
   - Open `script.js`
   - Replace the API key:
   ```js
   const API_KEY = "YOUR_API_KEY_HERE";
   ```

4. **Run the app:**
   - Open `index.html` in your browser
   
   **OR**
   
   - Use Live Server (recommended)

---

## 🙌 Author

**Abdur Rahim**

---

⭐ If you like this project, don't forget to give it a star!