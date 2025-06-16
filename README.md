# 🔥 Algerian Forest Fire Prediction - Ridge and Lasso Regression
This project is about predicting the Fire Weather Index (FWI) using weather data from the Algerian Forest Fires dataset. The goal is to use machine learning models like Linear Regression, Ridge Regression, and Lasso Regression to understand how different weather conditions affect forest fires.

## 📂 Dataset
- **Source:** Algerian Forest Fires Dataset

- **Features include:** Temperature, Relative Humidity, Wind Speed, Rain, FFMC, DMC, DC, ISI, BUI, FWI, etc.

- **Target:** FWI (Fire Weather Index)

## 🔍 Project Workflow
**1. Data Cleaning**

- Removed irrelevant columns like "day", "month", "year"

- Encoded categorical features

Exploratory Data Analysis (EDA)

Heatmaps, pairplots, and correlation matrix to study relationships

Distribution of FWI across fire/no-fire conditions

Feature Selection

Based on correlation and domain understanding

Modeling

Applied:

Linear Regression

Ridge Regression

Lasso Regression

Model Evaluation

Metrics used:

Mean Absolute Error (MAE)

Mean Squared Error (MSE)

Root Mean Squared Error (RMSE)

R² Score

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
