
# 🌦️ Weather App

A **web application** to get real-time weather information based on the user's location or any city name.  
It provides detailed weather data, including:  
🌡️ **Temperature** • 🤗 **Feels-like** • 🌅 **Sunrise** • 🌇 **Sunset** • 🌬️ **Wind Speed** • ☁️ **Cloudiness** • 💧 **Humidity**  

---

## ✨ Features

- **📍 Your Weather**: Automatically fetches and displays the weather report for the user's current location.  
- **🔍 Search by City**: Look up the weather of any city by entering its name.  
- **📊 Weather Data**: Includes:  
  - 🌡️ Current temperature  
  - 🤗 Feels-like temperature  
  - 🌅 Sunrise time  
  - 🌇 Sunset time  
  - 🌬️ Wind speed  
  - ☁️ Cloudiness  
  - 💧 Humidity  

---

## ⚙️ Installation

1. **Clone the repository**  
   ```sh
   git clone https://github.com/tauqueeralam42/weather-web-app.git
````

2. **Navigate to the project directory**

   ```sh
   cd weather-web-app
   ```
3. **Run the app**
   Open `index.html` in your browser.

---

## 🚀 Usage

1. Allow location access when prompted to get weather information for your current location.
2. Enter a city name in the search bar to get weather details for that city.

---

## 🌍 API Information

This app uses the [OpenWeatherMap API](https://openweathermap.org/api) to fetch weather data. You’ll need an API key.

1. Sign up at [OpenWeatherMap](https://home.openweathermap.org/users/sign_up)
2. Get your API key.
3. Replace the placeholder in `index.js` with your actual API key:

   ```javascript
   const API_KEY = 'YOUR_API_KEY';
   ```
4. API Endpoints:

   * **By coordinates**

     ```javascript
     `https://api.openweathermap.org/data/2.5/weather?lat=${lat}&lon=${lon}&appid=${API_KEY}&units=metric`
     ```
   * **By city name**

     ```javascript
     `https://api.openweathermap.org/data/2.5/weather?q=${city}&appid=${API_KEY}&units=metric`
     ```

---

## 🤝 Contributing

Contributions are welcome! Please open an issue or submit a pull request.

1. Fork the repository
2. Create a new branch

   ```sh
   git checkout -b feature-branch
   ```
3. Make your changes
4. Commit your changes

   ```sh
   git commit -m 'Add some feature'
   ```
5. Push to your branch

   ```sh
   git push origin feature-branch
   ```
6. Open a pull request

---

## 📸 Screenshots

> *(Add screenshots here to make your project visually appealing)*

---

## 📬 Contact

For any questions or suggestions:

* GitHub: [Ritik13012002](https://github.com/Ritik13012002)
* Email: **[ritiksingh1312002@gmail.com](mailto:ritiksingh1312002@gmail.com)**

---

**⭐ If you like this project, give it a star on GitHub!**

```

