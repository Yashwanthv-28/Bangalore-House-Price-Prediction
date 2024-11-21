## Bangalore House Price Prediction
A web application that estimates the price of houses in Bangalore based on user-provided inputs like location, area, availability status, square footage, number of bedrooms, and bathrooms.

## Features
- User-Friendly Interface: Intuitive and responsive design for seamless user experience.
- Dynamic Dropdowns: Location, area, and availability options are fetched dynamically using Flask APIs.
- Accurate Predictions: Powered by machine learning models trained on real-world Bangalore housing data.
- Backend Integration: Flask backend for seamless communication with machine learning models.
- Interactive Dashboard: Live and dynamic form inputs with real-time price predictions.

## Tech Stack
# Frontend
- HTML5, CSS3, JavaScript
- Bootstrap for responsive UI
- jQuery for AJAX calls
# Backend
- Flask for handling HTTP requests
- Python for business logic and ML model integration
- JSON APIs for dynamic data fetching
# Machine Learning
- Models used: Random Forest, XGBoost
- Data: Bangalore housing dataset

## Setup Instructions
### **1. Clone the Repository**
To clone the repository and navigate to the project directory, run the following commands:

```bash
git clone https://github.com/YashwanthV28/bangalore-house-price-prediction.git
cd bangalore-house-price-prediction
```
### **2. Set Up the Environment**
Install Python dependencies by running the following command:

```bash
pip install -r requirements.txt
```
### **3. Load Model and Data**
Ensure the following files are placed in the appropriate directory:

- **`model.pkl`**: The trained machine learning model file.
- **`columns.json`**: File containing feature names for predictions.

### **4. Run the Application**
Start the Flask server by running the following command:

```bash
python app.py
```
Access the application at http://127.0.0.1:5000

## Data Collection :
The dataset used for this project is obtained from Kaggle. You can access it here:
Bengaluru House Price Data


## **Project Structure**
The project is organized as follows:

```plaintext
.
├── static/                   # Static files (CSS, JS, images)
├── templates/                # HTML templates
├── BangalorePricePrediction.py  # Core prediction logic
├── app.py                    # Flask application
├── model.pkl                 # Machine learning model
├── requirements.txt          # Python dependencies
└── README.md                 # Project documentation
```

## Screenshots
![Screen shot](https://github.com/Yashwanthv-28/img/blob/bd448f1dac52af99d2cc3634ce4a8313ec64cbb3/123.png)
![Prediction Page Screenshot](https://github.com/Yashwanthv-28/img/blob/bd448f1dac52af99d2cc3634ce4a8313ec64cbb3/456.png)
## License
This project is licensed under the MIT License. Feel free to use and modify it.
