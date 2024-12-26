# AI-Driven Temperature Control System

This repository contains an AI-driven system for maintaining indoor comfort while optimizing energy efficiency. The project leverages machine learning and real-time weather data to dynamically adjust indoor temperature.

---

## Features
- **Indoor Temperature Prediction**: Uses real-time weather data (humidity, wind speed, pressure) to predict indoor temperature.
- **Dynamic Adjustment**: Automatically adjusts heating or cooling to maintain a stable indoor temperature around 20°C.
- **Real-Time Integration**: Fetches live weather data using OpenWeatherMap API.

---

## Project Structure
- **`data/`**: Contains historical weather data for model training.
- **`model/`**: Saved machine learning models in `.pkl` format.
- **`scripts/`**: Python scripts for training, preprocessing, and real-time implementation.
- **`notebooks/`**: Jupyter Notebooks for analysis and model development.

---

## How It Works
1. **Data Collection**:
   - Historical weather data.
   - Real-time updates from OpenWeatherMap API.
2. **Model Training**:
   - Models evaluated: Linear Regression, Ridge, Lasso.
   - Best model: Random Forest for real-time predictions.
3. **Real-Time Implementation**:
   - Predict indoor temperature.
   - Adjust temperature dynamically using AI-based logic.

---

## Technologies Used
- **Programming Language**: Python
- **Libraries**: 
  - Data Processing: `Pandas`, `NumPy`
  - Machine Learning: `scikit-learn`
  - Visualization: `Matplotlib`
  - API Integration: `requests`
  - Model Saving: `joblib`

---

## Getting Started
### Clone the repository:
```bash
git clone https://github.com/your-username/AI-Temperature-Control-System.git

## Install required packages:
- pip install -r requirements.txt

---


## Results
- **Model Evaluation**:
  - **Linear Regression**: RMSE = **2.90**
  - **Ridge Regression**: RMSE = **2.90**
  - **Lasso Regression**: RMSE = **3.19**

---



## Future Improvements
- Collect additional weather data to improve accuracy.
- Explore advanced algorithms such as neural networks.
- Integrate with IoT-enabled smart thermostats for enhanced automation.

---

## License
_ This project is licensed under the MIT License.



## Author
**George Glor**  
Email: georgeglor40@hotmail.com


