# Head Size and Brain Weight Analysis

This project demonstrates a simple linear regression analysis on a dataset containing measurements of head size in cm³ and brain weight in grams. The analysis is performed using both manual calculation and the `scikit-learn` library.

## Project Structure

- `linear_regression_with_r_square_method.py`: This script performs linear regression manually using numpy. It calculates the coefficients \( b_0 \) and \( b_1 \) using the formula for simple linear regression and plots the regression line. Additionally, it calculates the R-squared value to evaluate the goodness of fit.

- `linear_regression_by_scikit_learn.py`: This script performs linear regression using the `LinearRegression` model from the `scikit-learn` library. It also calculates the Root Mean Squared Error (RMSE) and the R-squared value to compare the results with the manual approach.

## Dataset

The dataset used in this analysis is `headbrain.csv`, which contains two columns:

- `Head Size(cm^3)`: The head size in cubic centimeters.
- `Brain Weight(grams)`: The brain weight in grams.

## Steps Involved in Analysis Project

1. **Data Loading**: The dataset is loaded using pandas.
2. **Data Analysis**: 
   - In `manual_regression.py`, the coefficients \( b_0 \) and \( b_1 \) are calculated using the formula for linear regression.
   - In `sklearn_regression.py`, the `LinearRegression` model is trained on the dataset.
3. **Visualization**: The regression line is plotted along with the scatter plot of the data points.
4. **Model Evaluation**:
   - The R-squared value is calculated in both approaches to check the goodness of fit.
   - The RMSE is also calculated in the `sklearn_regression.py` script.


## Results

Both scripts will output the regression coefficients and the R-squared value. The calculated R-squared value for this analysis is approximately **0.6393**, indicating that around 63.93% of the variance in brain weight can be explained by head size.

The `sklearn_regression.py` script will additionally output the Root Mean Squared Error (RMSE).

## Conclusion

This project showcases how to implement simple linear regression both manually and using a machine learning library. It also provides a comparison between the manual and automated approaches in terms of model evaluation metrics.
