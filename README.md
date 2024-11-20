# KrishiMitraApp
Krishi-Mitra: An Agri-Tech Application
Overview
Krishi-Mitra is an Android application developed in Kotlin that empowers farmers to make informed decisions about crop cultivation. By leveraging machine learning algorithms, the app predicts the best crops to grow based on location, weather conditions, and soil type. It also features a chatbot for user interaction and provides weather forecasts to further assist farmers in precision agriculture.

This project is a proof of concept (POC) and demonstrates the potential of integrating ML/DL techniques into precision farming for better agricultural outcomes.

Features
Crop Prediction: Suggests the best crops to grow based on location-specific weather conditions and soil type.
Weather Forecast: Provides real-time weather updates based on the user's location.
Interactive Chatbot: Offers an intuitive chatbot for user support and query resolution.
User-Friendly Interface: Designed with simplicity and ease of use for farmers in mind.
Tech Stack
Languages and Frameworks: Kotlin, FastAPI
APIs and Libraries:
Firebase: Realtime Database, Firestore, Firebase Storage
RetroFit: For HTTP requests
OkHTTP: For efficient networking
Rapid API: For chatbot integration
OpenWeather API: For weather data
Machine Learning:
Libraries: Numpy, Pandas, Scikit-Learn
Model: Random Forest
Cloud: GCP AMD Instance for ML model hosting
Setup and Requirements
Requirements:

Android Studio 4.0 or later
Android SDK 23 or later
Google Play Services
Steps to Run Locally:

Clone the repository:
bash
Copy code
git clone https://github.com/YourGitHubUsername/Krishi-Mitra.git  
Open the project in Android Studio.
Build and run the project on an emulator or a physical Android device.
Grant location and other required permissions.
Usage
Launch the app on your Android device.
Allow the app to access your location and required permissions.
Enter details like location and soil type.
View crop predictions, access the chatbot, and check the weather forecast.
API and ML Implementation
API Branch: The API implementation is available in the API branch.
Machine Learning: Check the ML branch for machine learning-related code.
FASTAPI Documentation: Refer to documentation here.
Chatbot Implementation: Powered by Rapid API.
Weather Data: Integrated using OpenWeather API.
