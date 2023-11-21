# Weather Bot

A simple Telegram bot that provides weather information for a given city using the OpenWeatherMap API.

## Prerequisites

Before you start, make sure you have the following:

- Python installed on your system.
- OpenWeatherMap API key. You can obtain one by signing up at [OpenWeatherMap](https://openweathermap.org/).

## Installation

1.Install the required Python packages:
pip install requests telebot

2.Replace 'YOUR_API_KEY' in the script with your actual OpenWeatherMap API key:
API_KEY = 'your_actual_api_key'

3.Run the script:
python weather_bot.py

## Usage
Start a chat with the Weather Bot on Telegram.
Send the name of a city to the bot.
Receive weather information for the specified city.

##Bot Commands
/start or /help: Display a welcome message with instructions.
(Any other message): Get the weather information for the specified city.

##Notes
The bot uses the OpenWeatherMap API to fetch weather data.
If the city name is not valid or weather data is not available, the bot will notify the user.

##Contributing
If you want to contribute to this project, feel free to fork the repository and submit a pull request. Please follow the coding style and conventions used in the project.

