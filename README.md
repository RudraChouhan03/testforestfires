# Algerian Forest Fire Prediction - Ridge and Lasso Regression

This project is about predicting the Fire Weather Index (FWI) using weather data from the Algerian Forest Fires dataset. The goal is to use machine learning models like Linear Regression, Ridge Regression, and Lasso Regression to understand how different weather conditions affect forest fires.

## Dataset

The dataset contains weather features like temperature, humidity, wind speed, rain, and fire indexes such as FFMC, DMC, DC, ISI, BUI, and FWI.

Target column: FWI (Fire Weather Index)

## Project Steps

1. Load and clean the dataset
2. Explore the data using graphs and summary statistics
3. Prepare the features and target variable
4. Split the data into training and testing sets
5. Apply Linear, Ridge, and Lasso regression models
6. Evaluate the models using error metrics like MAE, MSE, RMSE, and R2 score

## Results

After applying the models, Ridge Regression gave slightly better performance compared to Lasso and Elastic Net Regression.

| Model                  | R² Score |
| ---------------------- | -------- |
| Ridge Regression       |   0.984  |
| Lasso Regression       |   0.982  |
| Elastic Net Regression |   0.981  |


## Tools Used

- Python
- pandas and numpy for data handling
- seaborn and matplotlib for visualization
- scikit-learn for building and evaluating the models

## How to Run

1. Download the dataset and notebook
2. Open the notebook in Jupyter or any Python IDE
3. Run the cells step by step

## Acknowledgement

Thanks to Krish Naik sir for creating this helpful and practical course on data science and machine learning.

## Contact

If you have any suggestions or questions, feel free to reach out or connect with me on LinkedIn (http://www.linkedin.com/in/rudrachouhan).
