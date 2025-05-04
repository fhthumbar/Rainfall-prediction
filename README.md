# 🌧️ Rainfall Prediction Project

> Predicting daily rainfall in Austin, TX, using historical weather data and machine learning.

![License](https://img.shields.io/badge/license-MIT-blue.svg)  
![Python](https://img.shields.io/badge/python-3.8%2B-blue)

---

## 📂 Project Structure

```
├── austin_weather.csv         # Dataset
├── Rainfall_Prediction.ipynb  # Main Notebook
└── README.md                  # Project Documentation
```

---

## 🧐 Problem Statement

Accurately predicting rainfall can assist with water management, agriculture, and urban planning.  
This project aims to predict **daily precipitation** based on historical weather variables.

---

## 📊 Dataset

We used the `austin_weather.csv` dataset containing:

- 📅 Date  
- 🌡️ Avg Temperature (°F)  
- 💧 Avg Humidity (%)  
- 🌬️ Avg Wind Speed (MPH)  
- ☔ Precipitation (inches)

---

## 🚀 Methodology

1️⃣ **Data Cleaning**  
- Replaced non-numeric values ('T', '-') with `0`  
- Converted key columns to numeric  
- Dropped rows with missing values

2️⃣ **Feature Selection**  
- Selected: `TempAvgF`, `HumidityAvgPercent`, `WindAvgMPH`  
- Target: `PrecipitationSumInches`

3️⃣ **Model Building**  
- Trained **Linear Regression** model  
- Train-test split: 80%-20%

4️⃣ **Evaluation**  
- R² Score  
- Mean Squared Error (MSE)

---

## 🔍 Key Findings

- **Humidity** has the strongest positive correlation with precipitation  
- **Temperature** and **Wind Speed** have weaker relationships  
- Linear Regression showed **moderate predictive power** (see notebook output)

---

## 🛠️ Tech Stack

- Python 3  
- pandas  
- numpy  
- scikit-learn

---

## ⚙️ How to Run

1. Clone this repository
   ```bash
   git clone https://github.com/yourusername/rainfall-prediction.git
   cd rainfall-prediction
   ```

2. Install dependencies
   ```bash
   pip install pandas numpy scikit-learn
   ```

3. Open and run the notebook  
   *(Ensure `austin_weather.csv` is in the same directory)*

---

## 📈 Future Work

- Use advanced models (Random Forest, XGBoost)  
- Add more features (pressure, cloud cover)  
- Explore time-series methods

---

## 📝 License

This project is licensed under the MIT License — see the [LICENSE](LICENSE) file for details.

---

## ✨ Author

Made with ❤️ by **[FEVIN THUMBAR]**  
[GitHub Profile](https://github.com/fhthumbar)
