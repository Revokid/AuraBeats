# AuraBeats

AuraBeats is a web application that provides personalized weather and music recommendations based on the user’s mood and current weather conditions. Users can input their city to get real-time weather data, and the app will suggest music playlists that match both the weather and the selected mood.

Overview
AuraBeats fetches the current weather data for a given city and matches it with music tracks that fit the weather condition, making it an ideal companion to brighten your day.

Users can input a city and get the current weather conditions.
The app will then suggest music tracks suited to the weather.
The application is built using Node.js and Express.

Installation
Clone the repository: git clone 

Navigate to the project folder: cd AuraBeats

Create a .env file in the root of the project and add your API keys:
WEATHER_API_KEY=your_weatherapi_key
SPOTIFY_CLIENT_ID=your_spotify_client_id
SPOTIFY_CLIENT_SECRET=your_spotify_client_secret
PORT=3000

Install dependencies : npm i

Run the application: npm run dev
