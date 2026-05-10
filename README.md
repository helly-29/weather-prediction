#  Weather Prediction ML Project

A Machine Learning based Weather Prediction System built using Python, Scikit-learn, and Streamlit.

This project predicts:

- 🌡️ Temperature using Linear Regression
- 🌧️ Rain Prediction using Random Forest Classifier

The project also includes a Streamlit web application for interactive predictions.


##  Project Overview

This project performs:

- Data Cleaning
- Missing Value Handling
- Machine Learning Model Training
- Temperature Prediction
- Rainfall Prediction
- Data Visualization
- Model Saving & Loading
- Streamlit Web App Deployment

The goal is to analyze weather conditions and predict future weather outcomes using Machine Learning algorithms.


##  Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Streamlit
- Pickle


##  Machine Learning Algorithms Used

###  Linear Regression
Used for:
- Temperature Prediction

###  Random Forest Classifier
Used for:
- Rain Prediction


##  Dataset Features

Dataset includes weather parameters such as:

- MinTemp
- MaxTemp
- WindGustSpeed
- Humidity
- Pressure
- RainTomorrow


## Features Implemented

###  Data Preprocessing

- Missing Value Detection
- Null Value Removal
- Data Transformation

###  Machine Learning

- Train-Test Split
- Model Training
- Prediction
- Accuracy Evaluation
- Error Calculation

###  Data Visualization

- Actual vs Predicted Temperature Graph
- Rain Prediction Visualization

###  Model Serialization

- Saved models using Pickle
- Loaded models for prediction

###  Streamlit UI

Interactive weather prediction web application with:
- User Input Fields
- Temperature Prediction
- Rain Forecast


##  Output

### Temperature Prediction
Predicts estimated temperature based on:
- Min Temperature
- Max Temperature
- Wind Speed
- Humidity
- Pressure

### Rain Prediction
Predicts whether it will rain tomorrow:
- YES
- NO

---

##  How to Run the Project

### 1️Clone Repository

```bash
git clone https://github.com/your-username/weather-prediction.git
```

---

### 2️ Install Required Libraries

```bash
pip install pandas numpy matplotlib scikit-learn streamlit
```

---

### 3️ Run Python File

```bash
python weather.py
```

---

### 4️ Run Streamlit App

```bash
streamlit run weather.py
```

---

##  Learning Outcomes

Through this project, I learned:

- Machine Learning Basics
- Regression Algorithms
- Classification Algorithms
- Data Preprocessing
- Model Evaluation
- Streamlit Web App Development
- Model Saving using Pickle


## 👩‍💻 Author

Helly Leuva


##  Future Improvements

- Add more weather parameters
- Improve prediction accuracy
- Deploy on Streamlit Cloud
- Add real-time weather API
- Create advanced dashboard visualizations
