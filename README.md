# Task-3

Task 3: Linear Regression – House Price Prediction

This task involved building and evaluating a Linear Regression model to predict house prices using features like area, bedrooms, bathrooms, furnishing status, and more.

Steps I Followed:

1. Loaded the Dataset:

    Imported the housing dataset (Housing.csv) using Pandas.

2. Data Preprocessing:

     Checked for missing values, 
     Converted categorical columns (like furnishingstatus, mainroad) into numeric using pd.get_dummies()

3. Feature & Target Selection:

    Defined features (X) by dropping the price column
    Set price as the target variable (y)

4. Data Splitting:

    Split the data into training and testing sets (80% train, 20% test)

5. Model Training:

    Trained a Linear Regression model using sklearn.linear_model.LinearRegression

6. Model Evaluation:

    Calculated evaluation metrics: Mean Absolute Error (MAE), Mean Squared Error (MSE), R² Score
    Plotted Actual vs Predicted prices using a line graph

7. Feature Importance:
   
     Displayed model coefficients to show how each feature affects the predicted price


Libraries Used:
pandas, numpy, matplotlib,
sklearn.model_selection, sklearn.linear_model, sklearn.metrics

Visualized feature importance using a bar graph

