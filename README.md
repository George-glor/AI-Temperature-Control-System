AI-Driven Temperature Control System
This repository contains an AI-driven system for maintaining indoor comfort while optimizing energy efficiency. The project leverages machine learning and real-time weather data to dynamically adjust indoor temperature.

Features
Predicts indoor temperature based on real-time weather parameters (humidity, wind speed, and pressure).
Automatically adjusts heating or cooling to maintain a stable indoor temperature around 20°C.
Uses a trained Random Forest model for accurate predictions.
Integration with OpenWeatherMap API for real-time weather updates.
Project Structure
data/: Contains historical weather data for model training.
model/: Trained machine learning models saved as .pkl files.
scripts/: Python scripts for model training, data preprocessing, and real-time implementation.
notebooks/: Jupyter Notebooks for exploratory data analysis and model development.
How It Works
Data Collection: Historical weather data and real-time data from OpenWeatherMap API are used.
Model Training: Machine learning models (Linear Regression, Lasso, Ridge) were evaluated, with Random Forest selected for implementation.
Real-Time Implementation: Predicts indoor temperature using real-time weather data and adjusts the temperature dynamically.
Technologies Used
Python
Pandas and NumPy for data preprocessing
Scikit-learn for machine learning
Matplotlib for data visualization
Requests for real-time weather data from OpenWeatherMap API
Joblib for saving and loading models
Getting Started
Clone the repository:
bash
Copy code
git clone https://github.com/your-username/AI-Temperature-Control-System.git
Install required packages:
bash
Copy code
pip install -r requirements.txt
Add your OpenWeatherMap API key in config.py:
python
Copy code
API_KEY = "your_api_key"
Run the real-time temperature adjustment script:
bash
Copy code
python scripts/real_time_temperature_control.py
Results
Model Evaluation:
Linear Regression: RMSE = 2.90
Ridge Regression: RMSE = 2.90
Lasso Regression: RMSE = 3.19
The system successfully maintains a stable indoor temperature with minimal energy consumption.
Future Improvements
Collect more data to improve model accuracy.
Integrate advanced algorithms like neural networks.
Develop an IoT-compatible thermostat for seamless integration.
License
This project is licensed under the MIT License.

Author
George Glor

