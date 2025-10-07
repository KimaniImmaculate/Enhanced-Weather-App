# 🌤️ Enhanced Weather App

An **interactive, feature-rich weather application** built with **HTML, CSS, and Vanilla JavaScript**.  
It provides **real-time weather data**, a **5-day forecast**, **search history**, **geolocation detection**, and a **Celsius/Fahrenheit toggle**. The app is **deployed on GitHub Pages** for easy access.  


## **Live Demo**
Check out the live app here:  
[**Open Enhanced Weather App**](https://kimaniimmaculate.github.io/Enhanced-Weather-App/)  

## Add Your API Key

1. Open `script2.js`.  
2. Find this line:

```JavaScript
const API_KEY = 'YOUR_API_KEY';
```
3. Replace 'YOUR_API_KEY' with your OpenWeatherMap API key.
4. You can get a free key by signing up at [**OpenWeatherMap**](https://home.openweathermap.org/api_keys)

## **Features**

- 🌍 **Geolocation Detection:** Automatically detects your current city.  
- 📅 **5-Day Forecast:** View weather for the next 5 days, including temperature, humidity, wind, and weather icons.  
- 🔄 **Celsius/Fahrenheit Toggle:** Switch temperature units easily.  
- 🔍 **Search History:** Stores the last 5 searched cities for quick access.  
- 💾 **Persistent Storage:** Search history saved using **localStorage**.  
- 🎨 **Improved UI/UX:** Responsive design, clean layout, and subtle animations.  


## Usage

1. Enter a city in the search box **or allow geolocation detection**.  
2. View the **current weather** and **5-day forecast**.  
3. Toggle between **Celsius and Fahrenheit**.  
4. Click previous searches in the **search history** to quickly view the weather again.  
5. Refreshing the page will **retain search history** using localStorage.  

## Technologies Used

- HTML5  
- CSS3 (Flexbox, Grid, Animations)  
- JavaScript (ES6+)  
- OpenWeatherMap API  
- LocalStorage for persistent search history  
- GitHub Pages for deployment

