🏠 **Boston Housing Price Prediction & Power BI Dashboard**

This project is a comprehensive end-to-end analysis and prediction model built on the Boston Housing dataset, integrating machine learning techniques with business intelligence visualization through Power BI. It aims to provide data-driven insights into the factors influencing housing prices and present them through interactive, easy-to-understand visuals.

📁 Project Files
housing_project.ipynb – Jupyter notebook containing data preprocessing, visualization, and price prediction models.

Power BI .pbix file – Interactive dashboard for exploring various aspects of the Boston housing dataset.

🚀 Project Objectives
Understand and analyze the Boston Housing dataset using EDA.

Build regression models to predict housing prices.

Visualize trends and relationships using Power BI.

Provide insights using both statistical and visual analysis.

🧠 Machine Learning Workflow (Jupyter Notebook)
The notebook (housing_project.ipynb) includes a complete pipeline for predictive modeling:

🔹 Data Preprocessing
Handling missing values

Renaming columns for clarity

Encoding categorical variables (e.g., CHAS)

Train-test splitting using scikit-learn

🔹 Feature Engineering
Feature Scaling: Applied standardization to normalize feature distributions for better model performance.

Polynomial Features: Generated additional features using polynomial combinations to capture non-linear relationships.

L2 Regularization (Ridge Regression): Used to reduce model complexity and prevent overfitting.

Cross-Validation: Employed K-Fold Cross Validation to ensure model generalization and avoid data leakage.

🔹 Models Used
Linear Regression (Baseline model)

Ridge Regression with L2 penalty and optimized hyperparameters

Evaluation metrics:

R² Score

Mean Absolute Error (MAE)

The models were tuned, validated, and compared to select the best performing configuration for reliable price prediction.

📊 Power BI Dashboard
The Power BI dashboard was built to provide a business-oriented perspective of the data and support visual exploration. It includes:

📈 Page 1:
KPI Cards: Max, Min, Average of PRICE and TAX

Pie Chart: Distribution of homes based on RAD (accessibility to highways)

Histogram: Price distribution across all houses

Scatter Plots:

LSTAT vs PRICE: Shows a negative correlation between lower economic status and house price

AGE vs PRICE: Relationship between age of houses and their prices

RM vs PRICE: Strong positive correlation between number of rooms and price

📉 Page 2:
Correlation Heatmap: Displays relationships between features like LSTAT, RM, PTRATIO, and PRICE

Bar Chart: Aggregated view of PRICE and RM by RAD and CHAS

Conditional Formatting Table: Highlights patterns in features such as TAX, CRIM, and PRICE

Interactive Filters:

Slicers for CHAS, RAD, PRICE range, and RM (number of rooms)

Users can dynamically filter visuals to explore data segments



📌 Key Learnings
Hands-on with data cleaning and visualization using Python (Pandas, Matplotlib, Seaborn).

Built and evaluated regression models (Linear Regression, Ridge Regression etc.).

Designed interactive visuals using Power BI.

Learned to combine ML insights with BI tools for better decision-making.

📦 Technologies Used
Python (Jupyter Notebook)

Power BI

Pandas, NumPy, Matplotlib, Seaborn

Scikit-learn

✅ How to Use
Clone this repository.

Run housing_project.ipynb to explore and run the ML models.

Open the .pbix file using Power BI Desktop to interact with the dashboard.

