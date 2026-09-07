# Weather Predictor

A full-stack weather forecasting application that provides current weather conditions, hourly forecasts, and weekly weather predictions. The application also includes an AI-powered weather assistant that allows users to ask questions about weather conditions and forecasts.

The project is built using React and Spring Boot, with Open-Meteo used as the weather data provider.

---

# Overview

Weather Predictor is designed as a modern weather application where users can search for cities and view detailed weather information in a simple interface.

The application provides:

- Current weather information
- Hourly weather forecasts
- 7-day weather forecasts
- Temperature, humidity, wind, and precipitation details
- City-based weather search
- Temperature unit conversion between Celsius and Fahrenheit
- AI-powered weather-related questions and answers
- Cached weather data for improved performance
- Mock data fallback when the backend is unavailable

---

# Features

# Current Weather

Displays the current weather conditions of the selected city, including temperature, humidity, weather condition, wind information, and precipitation details.

# Hourly Forecast

Provides weather information for the upcoming hours, allowing users to track temperature and weather changes throughout the day.

# Weekly Forecast

Displays a 7-day weather forecast with daily high and low temperatures along with precipitation probability.

# City Search

Users can search and select from supported cities to view weather information for different locations.

# AI Weather Assistant

The application includes an AI-powered assistant that can answer weather-related questions based on the available forecast data.

# Temperature Unit Conversion

Users can switch between Celsius and Fahrenheit depending on their preference.

# Responsive User Interface

The frontend uses a modern glassmorphism-inspired design with smooth animations and responsive layouts.

---

# Tech Stack

# Frontend

- React 19
- Vite
- Framer Motion
- Vanilla CSS

# Backend

- Java 17
- Spring Boot 3.2
- Spring WebFlux
- WebClient
- Caffeine Cache

# APIs and Services

- Open-Meteo API
- AI/LLM integration for the weather assistant

---

# Project Architecture

```text
Weather Predictor
│
├── frontend
│   ├── React 19
│   ├── Vite
│   ├── Framer Motion
│   └── Vanilla CSS
│
├── backend
│   ├── Spring Boot
│   ├── Java 17
│   ├── WebFlux
│   ├── WebClient
│   └── Caffeine Cache
│
└── README.md

Running the Project

Folks, running this project is pretty straightforward. Start by navigating to the backend folder and run the Spring Boot application using the Maven wrapper. Once the backend is up and running on port 8080, move to the frontend folder, install the required dependencies using npm, and start the Vite development server. The application will then be available in your browser on port 5173. Just make sure both the frontend and backend are running properly for the complete application to work.

Prerequisites
Make sure you have the following installed:
Java 17 or later
Node.js
npm
Maven or Maven Wrapper


# Future Improvements

Some possible improvements for the project include:
Adding location detection using browser geolocation
Supporting more cities and countries
Adding weather alerts and notifications
Saving favourite locations
Adding user authentication
Improving AI assistant capabilities
Adding historical weather data
Deploying the application using cloud infrastructure you can refine the deployment strategy based on your preferences and requirements.



Author
Mohammed Saad
IT Corporate Trainer and Software Developer with an interest in building practical applications and helping learners understand technology through hands-on projects.Passionate about creating user-friendly applications that provide real value to users. Skilled in full-stack development, with experience in React, Spring Boot, and various APIs.

# License
This project is licensed under the MIT License.
Feel free to use, modify, and learn from the project also, but please give credit to the  author and respect the license terms.