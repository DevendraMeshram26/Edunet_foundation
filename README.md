# Edunet_foundation
# Energy Consumption Prediction

## Project Overview
This project aims to predict energy consumption based on various factors such as temperature, humidity, power usage, and other relevant features. The goal is to build a machine learning model that can accurately forecast energy consumption, helping in resource optimization and efficiency improvements.

## Dataset
- The dataset consists of multiple features affecting energy consumption.
- The target variable is **EnergyConsumption**.

## Models Used
- **Linear Regression**
- **Random Forest Regressor**

## Implementation Steps
1. **Data Preprocessing**
   - Handling missing values
   - Feature selection
   - Data normalization

2. **Exploratory Data Analysis (EDA)**
   - Visualizing data distributions

3. **Model Training & Evaluation**
   - Train-Test Split (80-20%)
   - Model fitting
   - Performance evaluation using MAE, MSE, R² Score

## Results
- The best model was **Linear Regression** with an R² score of **0.5967100801907437**.
- The model showed good accuracy in predicting energy consumption.

## Future Enhancements
- Try additional models like **LSTMs for time-series forecasting**.
- Implement **hyperparameter tuning** to improve model performance.
- Deploy the model using **Flask or Streamlit**.

## How to Run the Project
1. Upload the dataset to Google Colab.
2. Run `energy_consumption_analysis.py`.
3. Check the predictions and evaluation metrics.

## Dependencies
```bash
pip install pandas numpy scikit-learn matplotlib seaborn xgboost tensorflow
```

## Author
- **Devendra Meshram**

Feel free to contribute and improve this project!

