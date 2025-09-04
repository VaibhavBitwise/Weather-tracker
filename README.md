🌦️ Voice-Enabled Weather App

An interactive Weather App built with Python (Tkinter GUI) and the OpenWeatherMap API.
It lets users speak a city name to instantly fetch real-time weather data including temperature, humidity, wind speed, and conditions.
The app also features dynamic backgrounds that change based on the current weather (sunny, rainy, cloudy, stormy, etc.).

🚀 Features

🎤 Voice Input – Speak the city name using speech recognition.

🌍 Live Weather Data – Fetches details from the OpenWeatherMap API.

🎨 Dynamic Backgrounds – Weather-based background images (sunny, rainy, cloudy, stormy).

🌡️ Displays temperature, humidity, wind speed, and condition summary.

🖥️ Tkinter GUI with responsive and interactive design.

🛠️ Technologies Used

Python 🐍

Tkinter (GUI library)

OpenWeatherMap API

Pillow (PIL) – for image handling

SpeechRecognition (Google Speech API)

📂 Project Structure
Voice-Weather-App/
│── weather_app.py        # Main application file
│── README.md             # Project documentation
│── assets/               # Folder for background images (sunny, rainy, cloudy, etc.)

▶️ How to Run

Clone this repository:

git clone https://github.com/VaibhavBitwise/Weather-tracker.git
cd voice-weather-app


Install required libraries:

pip install requests pillow SpeechRecognition


Get a free API key from OpenWeatherMap
.

Open weather_app.py and replace the api_key variable with your key.

Run the app:

python weather_app.py


🎤 Speak your city name when prompted and see the live weather with dynamic background!

🌟 Future Improvements

Add 7-day weather forecast.

Include map integration to select cities visually.

Add dark mode toggle for UI customization.

Support for multiple languages in voice recognition.
