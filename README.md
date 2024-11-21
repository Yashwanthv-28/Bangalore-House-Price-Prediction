## Bangalore House Price Prediction
A web application that estimates the price of houses in Bangalore based on user-provided inputs like location, area, availability status, square footage, number of bedrooms, and bathrooms.

## Features
User-Friendly Interface: Intuitive and responsive design for seamless user experience.
Dynamic Dropdowns: Location, area, and availability options are fetched dynamically using Flask APIs.
Accurate Predictions: Powered by machine learning models trained on real-world Bangalore housing data.
Backend Integration: Flask backend for seamless communication with machine learning models.
Interactive Dashboard: Live and dynamic form inputs with real-time price predictions.

## Tech Stack
# Frontend
HTML5, CSS3, JavaScript
Bootstrap for responsive UI
jQuery for AJAX calls
# Backend
Flask for handling HTTP requests
Python for business logic and ML model integration
JSON APIs for dynamic data fetching
# Machine Learning
Models used: Random Forest, XGBoost
Data: Bangalore housing dataset

## Setup Instructions
# 1. Clone the Repository
git clone https://github.com/YashwanthV28/bangalore-house-price-prediction.git
cd bangalore-house-price-prediction
# 2. Set Up the Environment
Install Python dependencies:
pip install -r requirements.txt
# 3. Load Model and Data
Ensure the machine learning model file and attributes (e.g., model.pkl and columns.json) are placed in the appropriate directory.
# 4. Run the Application
Start the Flask server:
python app.py
Access the application at http://127.0.0.1:5000

## Data Collection :
The dataset is obtained from Kaggle. 
Link: https://www.kaggle.com/amitabhajoy/bengaluru-house-price-data

## Project Structure
.
├── static/                   # Static files (CSS, JS, images)
├── templates/                # HTML templates
├── BangalorePricePrediction.py  # Core prediction logic
├── app.py                    # Flask application
├── model.pkl                 # Machine learning model
├── requirements.txt          # Python dependencies
└── README.md                 # Project documentation

## Screenshots

## License
This project is licensed under the MIT License. Feel free to use and modify it.
