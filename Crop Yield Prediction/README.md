# Crop Yield Prediction

## Overview  
This project focuses on predicting crop yield using environmental and agricultural factors such as rainfall, temperature, fertilizer usage, and soil nutrients. The goal is to understand the key drivers of yield and build machine learning models that can accurately estimate crop productivity.

---

## Dataset Description  

The dataset consists of the following features:

| Feature | Description |
|--------|------------|
| Rain Fall (mm) | Rainfall in millimeters |
| Temperature (°C) | Temperature in Celsius |
| Fertilizer | Amount of fertilizer used |
| Nitrogen (N) | Nitrogen content in soil |
| Phosphorus (P) | Phosphorus content in soil |
| Potassium (K) | Potassium content in soil |
| Yield (Q/acre) | Crop yield |

---

## Data Preprocessing  

- Invalid values in the temperature column were removed  
- Data types were corrected where required  
- Missing values were handled using median imputation  
- Dataset was prepared for modeling and analysis  

---

## Exploratory Data Analysis  

Exploratory analysis was performed to understand patterns and relationships in the data.  

- Strong positive relationships were observed between yield and rainfall, fertilizer, and nutrients  
- Temperature showed a strong negative relationship with yield  
- Correlation analysis indicated possible multicollinearity among fertilizer-related features  
- Distribution plots showed that Random Forest predictions align more closely with actual values  

---

## Model Building  

Two regression models were implemented:

- Decision Tree Regressor  
- Random Forest Regressor  

The models were trained on the dataset and evaluated using standard regression metrics.

---

## Results  

- Random Forest outperformed Decision Tree in terms of prediction accuracy  
- It produced more stable and consistent predictions  
- Feature importance analysis showed temperature and rainfall as the most influential variables  

---

## Key Insights  

- Yield increases with higher rainfall and nutrient availability  
- Temperature acts as a limiting factor and negatively impacts yield  
- Some input features are highly correlated and may be redundant  
- Random Forest provides better generalization compared to Decision Tree  

---

## Conclusion  

This project demonstrates how environmental and soil factors influence crop yield. Among all variables, temperature and rainfall play a dominant role, while nutrients further enhance productivity. The Random Forest model proved to be more reliable for prediction, making it a suitable choice for this problem.

---

## Future Work  

- Include more features such as soil type, crop type, and humidity  
- Perform hyperparameter tuning for improved performance  
- Experiment with advanced models like XGBoost or Gradient Boosting  
- Deploy the model as a web application  
