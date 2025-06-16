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

**2. Exploratory Data Analysis (EDA)**

- Heatmaps, pairplots, and correlation matrix to study relationships

- Distribution of FWI across fire/no-fire conditions

**3. Feature Selection**

- Based on correlation and domain understanding

**4. Modeling**

- Applied:

    - **Linear Regression**

    - **Ridge Regression**

    - **Lasso Regression**
      
    - **Elastic Net Regression**

**5. Model Evaluation**

- Metrics used:

    - Mean Absolute Error (MAE)

    - Mean Squared Error (MSE)

    - Root Mean Squared Error (RMSE)

    - R² Score

## 📈 Results Summary

After applying the models, Ridge Regression gave slightly better performance compared to Lasso and Elastic Net Regression.

| Model                  | R² Score |
| ---------------------- | -------- |
| Ridge Regression       |   0.984  |
| Lasso Regression       |   0.982  |
| Elastic Net Regression |   0.981  |


## 🛠️ Tools & Libraries

- Python
- Pandas and NumPy for data handling
- Seaborn and Matplotlib for visualization
- Scikit-learn for building and evaluating the models

## 🚀 How to Run

1. Download the dataset and notebook
2. Open the notebook in Jupyter or any Python IDE
3. Run the cells step by step

## 🙏 Acknowledgement

Thanks to [Krish Naik](https://www.linkedin.com/in/naikkrish) sir  for providing the amazing content and project guidance as part of the Data Science & ML course.

## Contact

If you have any suggestions or questions, feel free to reach out or connect with me on 

📧 rudrachouhan0305@email.com

🔗 [LinkedIn](http://www.linkedin.com/in/rudrachouhan)
