🔥 Forest Fire Weather Index (FWI) Prediction
A Machine Learning web application that predicts the Fire Weather Index (FWI) for Algerian forest fires using Ridge, Lasso, and Linear Regression models — deployed with Flask.

📌 Project Overview
Forest fires cause massive environmental damage. This project uses meteorological data (temperature, humidity, wind speed, and rain) to predict the Fire Weather Index, which indicates fire risk levels.

🛠️ Tech Stack
Python — core language
Scikit-learn — Ridge, Lasso, Linear Regression
Pandas & NumPy — data processing
Seaborn & Matplotlib — EDA and visualization
Flask — web app deployment
Pickle — model serialization


📁 Project Structure
Forest Fire Prediction Project/
│
├── models/
│   ├── ridge.pkl                          # Trained Ridge model
│   ├── scaler.pkl                         # Standard Scaler to normalise values
│   ├── Algerian_forest_fires_dataset.csv
│   └── Algerian_forest_fires_cleaned_dataset.csv  # Cleaned dataset after removing empty values
│
├── notebooks/
│   ├── Algerian Forest Fire dataset.ipynb  # EDA
│   ├── Model Training.ipynb                # Model training
│   └── Multi Linear Regression.ipynb       # Regression analysis
│
├── templates/
│   ├── home.html                           # Landing page
│   └── index.html                          # Prediction page
│
└── application.py                          # Flask app

🚀 How to Run Locally
bash# 1. Clone the repo
git clone https://github.com/YOUR_USERNAME/Forest-Fire-Prediction-Regression-Project.git

# 2. Install dependencies
pip install -r requirements.txt

# 3. Run the app
python application.py
Open http://127.0.0.1:5000 in your browser.

📊 Input Features
FeatureDescriptionTemperatureTemp in °CRHRelative Humidity (%)WsWind Speed (km/h)RainRainfall (mm)FFMCFine Fuel Moisture CodeDMCDuff Moisture CodeISIInitial Spread IndexClassesFire / Not FireRegionBejaia / Sidi Bel-abbes

📈 Models Used
Linear Regression — baseline model
Lasso Regression — L1 regularization
Ridge Regression — L2 regularization 


**Jatin Vimal**  
B.Tech Data Science & Engineering, IIT Palakkad  

[![LinkedIn](https://img.shields.io/badge/LinkedIn-blue?logo=linkedin)](https://www.linkedin.com/in/jatin-vimal-6831052b3/)
[![GitHub](https://img.shields.io/badge/GitHub-black?logo=github)](https://github.com/jatinvimal1506)
