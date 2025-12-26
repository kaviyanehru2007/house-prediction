House Price Prediction using Linear Regression
Description
This project predicts house prices using a Linear Regression model based on:
Square Footage
Number of Bedrooms
Number of Bathrooms
The dataset used is from Kaggle’s House Prices – Advanced Regression Techniques competition.
Dataset
Source: Kaggle
File used: train.csv
Link: https://www.kaggle.com/c/house-prices-advanced-regression-techniques/data
Technologies Used
Python
Pandas
NumPy
Matplotlib
Scikit-learn
Features Used
GrLivArea – Square Footage
BedroomAbvGr – Number of Bedrooms
FullBath – Number of Bathrooms
SalePrice – Target variable
Steps Performed
Load the dataset
Select required features
Handle missing values
Split data into training and testing sets
Train a Linear Regression model
Evaluate model using MSE and R² score
Predict house price for new input
How to Run
Copy code
Bash
pip install pandas numpy matplotlib scikit-learn
price_prediction.py
Model Evaluation
Mean Squared Error (MSE)
R² Score
Sample Prediction
Input:
2000 sq.ft
3 bedrooms
2 bathrooms
Output:
Predicted house price
Conclusion
This project shows how Linear Regression can be used to predict house prices using basic housing features. It is suitable for academic and internship submissions.
