# Weather App
A responsive and user-friendly Weather Application built using React and Vite. It fetches real-time weather data based on the user’s city input and displays temperature, humidity, wind speed, and weather conditions with dynamic icons.

Live Demo: https://weather-app-nu-blue-21.vercel.app/

## Features
- Real-time weather data fetching
- Search weather by city
- Dynamic weather icons
- Responsive UI
- Error handling
- Clean and modern interface

## Screenshot 
![Web Page Screenshot](src/assets/RockPaperScissorsGame.png)

## Technologies Used
- React
- Vite
- JavaScript (ES6+)
- CSS
- Weather API (OpenWeatherMap or similar)

## Folder Structure
project-folder/  
├── index.html  
├── src/  
│   ├── assets/    
│   ├── components/  
│   │   ├── Weather.jsx  
│   │   └── Weather.css  
│   ├── App.jsx  
│   ├── index.css  
│   └── main.jsx  
└── package.json  

## Environment Variables
Create a `.env` file in the root directory:
VITE_APP_ID=your_api_key_here

## How to Run
- npm install  
- npm run dev

## How It Works
1. User enters a city name.  
2. App sends an API request using the API key.  
3. Weather data is fetched and displayed.  
4. Weather icons update dynamically.  
5. Responsive UI adjusts for all screens.

## What I Learned
- Fetching API data in React  
- Managing state and conditional rendering  
- Using environment variables in Vite  
- Component-based architecture  
- Working with asynchronous data  

## Author
**Shruti Rawat**<br>
Web Developer
