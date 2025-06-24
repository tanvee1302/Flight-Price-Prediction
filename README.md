
# ✈️ Flight Fare Predictor

A machine learning web app that predicts flight ticket prices based on features like airline, departure time, source, and total stops. Powered by **CatBoostRegressor** and deployed with **Streamlit**.

---

## 📌 Project Summary

This project uses advanced regression techniques to predict flight prices with high accuracy.

- 🔢 **Model**: CatBoostRegressor  
- 📊 **MAE**: ₹790.93  
- 📈 **R² Score**: 0.87  
- 🧠 **Top Features**: `Duration_minutes`, `Airline`, `Journey_month`, `Total_Stops`  
- 🌐 **Deployment**: Streamlit (interactive UI)

---

## 🚀 Features

- Predicts ticket price based on:
  - Airline
  - Journey date and month
  - Total stops
  - Source & destination cities
  - Time of departure (e.g., Morning, Evening)
  - Duration in minutes
- Clean and responsive UI built with Streamlit
- Custom background image and dropdown selections for real-world UX
- Model trained on over **10,000+ real-world flight records**

---

## 📊 Dataset Overview

| Column             | Description                        |
|--------------------|------------------------------------|
| Airline            | Name of the airline                |
| Source             | Origin city                        |
| Destination        | Destination city                   |
| Total_Stops        | Number of stops in the journey     |
| Duration_minutes   | Total duration in minutes          |
| Journey_day        | Day of journey                     |
| Journey_month      | Month of journey                   |
| Dep_hour           | Hour of departure (binned)         |
| Additional_Info    | Extra info (meal, baggage, etc.)   |
| Price              | Target variable (₹)                |

---

## 📈 Model Details

- **Algorithm**: CatBoostRegressor
- **Hyperparameters**: 
  - Iterations: 1000  
  - Learning rate: 0.1  
  - Depth: 6  
- **Evaluation Metrics**:
  - Mean Absolute Error (MAE): ₹790.93
  - R² Score: 0.87

---

## 🖥️ Run Locally

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/flight-fare-predictor.git
cd flight-fare-predictor

pip install -r requirements.txt
