# Linear Regression with Python

## Overview

In this project, we build a Linear Regression model to predict housing prices based on various features. The dataset provided contains information about houses in different regions of the United States, including average area income, house age, number of rooms, and more. The goal is to create a model that can estimate house prices given these features.

## Libraries Used

- `pandas`: For data manipulation and analysis.
- `numpy`: For numerical computations.
- `matplotlib`: For data visualization.
- `seaborn`: For statistical data visualization.
- `scikit-learn`: For building and evaluating the Linear Regression model.

## Data

The dataset used is `USA_Housing.csv` and contains the following columns:

- `Avg. Area Income`: Average income of residents in the city.
- `Avg. Area House Age`: Average age of houses in the city.
- `Avg. Area Number of Rooms`: Average number of rooms in houses in the city.
- `Avg. Area Number of Bedrooms`: Average number of bedrooms in houses in the city.
- `Area Population`: Population of the city.
- `Price`: Price that the house sold for.
- `Address`: Address of the house (excluded from the model).

## Analysis Steps

1. **Import Libraries**: Load necessary libraries for data analysis and modeling.
2. **Load and Inspect Data**: Read the `USA_Housing.csv` file and inspect the data.
3. **Exploratory Data Analysis (EDA)**:
   - Visualize relationships between features and the target variable (`Price`).
   - Analyze the distribution of data and correlation between features.
4. **Data Preparation**:
   - Prepare features (`X`) and target variable (`y`).
   - Split the data into training and test sets.
5. **Model Training**:
   - Train the Linear Regression model using the training data.
6. **Model Evaluation**:
   - Evaluate the model by checking its coefficients.
   - Make predictions and evaluate the model using metrics such as Mean Absolute Error (MAE), Mean Squared Error (MSE), and Root Mean Squared Error (RMSE).

## Insights

- Coefficients for each feature indicate how each feature affects the price of the house.
- MAE, MSE, and RMSE provide insights into the model's performance and prediction accuracy.

## Conclusion

The Linear Regression model provides a useful tool for estimating housing prices based on various features. By understanding the coefficients and evaluating the model's performance, we can make informed predictions and insights about housing prices in different regions.

## Requirements

- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`
- `scikit-learn`

## Usage

1. Clone the repository:

   ```bash
   git clone <repository-url>
