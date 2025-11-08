# Forecasting-Wind-Turbine-Power-Output-using-Machine-Learning
A predictive model that estimates the power output of a wind turbine using weather and turbine parameters such as wind speed, air temperature, humidity, and pressure.

#### DATASET - The Wind Turbine Scada Dataset
(https://www.kaggle.com/datasets/berkerisen/wind-turbine-scada-dataset)

In Wind Turbines, Scada Systems measure and save data's like wind speed, wind direction, generated power etc. for 10 minutes intervals. This file was taken from a wind turbine's scada system that is working and generating power in Turkey.

---

## Data Loading & Cleaning
- Imported the dataset and checked for missing or inconsistent values.
- Removed or filled missing records where required.
- Ensured data types were properly formatted.

---
## Preprocessing
- Normalized and scaled numerical features for better model performance.
- Encoded categorical columns (if any) to numeric format.
- Handled outliers to maintain stable learning patterns.

---

## Feature Engineering
- Created relevant new features to enhance model interpretability.
- Selected key features that strongly influence the power output.

---

## Exploratory Data Analysis (EDA)
- Visualized relationships between wind speed, rotor speed, and power output.
- Detected patterns showing higher wind speeds generally relate to higher power generation.
- Identified correlations to aid in feature selection and modeling.

---

## Model Development

### Train-Test Split
- Divided the dataset into training and testing sets to evaluate model generalization.

### Models Used
1. **Linear Regression**
   - Simple baseline model.
   - Helps interpret feature relationships.
2. **XGBoost Regressor**
   - More advanced machine learning model.
   - Handles non-linear patterns and interactions.

---

## Evaluation
- Compared model predictions using metrics such as:
  - Mean Absolute Error (MAE)
  - Root Mean Squared Error (RMSE)
- XGBoost model showed superior performance over Linear Regression.

---

## Conclusion
- The XGBoost model provided more accurate predictions of turbine power output.
- This model can be used to support decision-making for energy forecasting and operational efficiency.

