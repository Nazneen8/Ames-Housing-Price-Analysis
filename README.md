# Ames-Housing-Price-Analysis

### Overview
This project uses linear regression to predict house prices based on property features. The aim is to understand how house size and garage size affect the sale price. 

### Objectives
- Analyse the relationship between house features and sale price
- Build a regression model using selected variables
- Evaluate the accuracy of the model
- Interpret the results and coefficients

### Dataset
The *Ames Housing dataset* was used.

The features used were:
 - Gr_Liv_Area - Living area (square feet)
 - Garage_Area - Garage size (square feet)

Target:
 - Sale_Price

### Model
A model linear regression model was built using:
- Gr_Liv_Area
- Garage_Area

The dataset was split into:
- 75% training data
- 25% testing data

Model performance was evaluated using RMSE, and results were analysed using a residual plot.

### How to Run
1. Clone the repository
2. Install required libraries
3. Open the notebook
4. Run Linear_Regression_Ames.ipynb

# Conclusion
The model shows that both living area and garage size have a positive impact on house prices. While the model captures general trends, its accuracy is limited due to the small number of features used. Including more variables would improve the performance.
