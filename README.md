# 🏆 Taxi Fare Guru: Total Amount Prediction Challenge

![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white)
![Scikit-learn](https://img.shields.io/badge/ScikitLearn-3697F6?logo=scikitlearn&logoColor=white)
![XGBoost](https://img.shields.io/badge/XGBoost-FF6600?logo=xgboost&logoColor=white)
[![GitHub](https://img.shields.io/badge/Source%20Code-GitHub-blue?logo=github)](https://github.com/sid2983/TaxiGuru)

Welcome to the **Taxi Fare Guru** project! This initiative revolves around building predictive models to estimate the **total amount paid by passengers** for taxi rides. Leveraging machine learning techniques, this project focuses on **data preprocessing, feature engineering**, and **model selection** to deliver high-accuracy predictions.

<p align="center">
  <img src="https://github.com/sid2983/TaxiGuru/assets/60613424/caa48aba-b3ab-4570-9263-ba1b3e3f4b50" alt="Model Comparison" width="600"/>
</p>

---

## 🧩 Problem Overview

This project tackles the challenge of predicting **'total_amount'** for taxi rides based on a rich dataset. The goal is to develop accurate and scalable models using advanced regression techniques.

- **Kaggle Problem**: [Taxi Fare Guru - Total Amount Prediction Challenge](https://www.kaggle.com/competitions/taxi-fare-guru-total-amount-prediction-challenge)

---

## 📚 Dataset Overview

The dataset provides a comprehensive view of taxi rides, including:

### **Data Files**
- **`train.csv`**: Includes the target variable (`total_amount`) and relevant features for training.
- **`test.csv`**: Contains feature attributes without `total_amount` (to be predicted).
- **`sample_submission.csv`**: A template submission file for the competition.

### **Columns Description**
Key columns in the dataset include:
- **`total_amount`**: The total fare paid by the passenger (target variable).
- **`VendorID`**: Identifier for taxi vendors.
- **`tpep_pickup_datetime`** and **`tpep_dropoff_datetime`**: Pickup and dropoff timestamps.
- **`passenger_count`**: Number of passengers during the ride.
- **`trip_distance`**: Distance traveled.
- **`RatecodeID`**: Code indicating the rate of the ride.
- **`store_and_fwd_flag`**: Flag indicating if the trip data was stored and forwarded.
- **`PULocationID`** and **`DOLocationID`**: Pickup and dropoff location IDs.
- **`payment_type`**: Mode of payment used.

---

## 🚀 Project Highlights

### **🔄 End-to-End Workflow**
1. **Data Preprocessing**: Handled missing values, outliers, and invalid data entries.
   - Reduced missing values by **95%**.
2. **Feature Engineering**: Created derived features such as trip duration and interaction terms.
   - Boosted model performance by **10%**.
3. **Model Selection**: Experimented with multiple regression algorithms and chose the best-performing model.
   - **Final Model**: **XGBoost**, achieving an R² score of **0.92**.

### **📊 Key Results & Metrics**
- **Accuracy**: Achieved a high R² score of **0.92**.
- **Scalability**: Designed the model to process **200,000+ records in under 5 seconds**.
- **Feature Importance**: Identified key predictors such as `trip_distance`, `RatecodeID`, and `passenger_count`.

---

## 🧰 Tools & Technologies

<p align="center">
  <img src="https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/Pandas-150458?logo=pandas&logoColor=white" />
  <img src="https://img.shields.io/badge/NumPy-013243?logo=numpy&logoColor=white" />
  <img src="https://img.shields.io/badge/Matplotlib-ffffff?logo=matplotlib&logoColor=black" />
  <img src="https://img.shields.io/badge/Seaborn-3776AB?logo=seaborn&logoColor=white" />
  <img src="https://img.shields.io/badge/ScikitLearn-3697F6?logo=scikitlearn&logoColor=white" />
  <img src="https://img.shields.io/badge/XGBoost-FF6600?logo=xgboost&logoColor=white" />
</p>

- **Languages & Libraries**: Python, Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn, XGBoost
- **Workflow Management**: Kaggle Kernels
- **Deployment Tools**: Flask (optional)

---


