<h1>🏠 Boston Housing Price Prediction & Power BI Dashboard</h1>

<p>This project is a comprehensive end-to-end analysis and prediction model built on the Boston Housing dataset, integrating machine learning techniques with business intelligence visualization through Power BI. It aims to provide data-driven insights into the factors influencing housing prices and present them through interactive, easy-to-understand visuals.</p>

<h2>📁 Project Files</h2>
<ul>
  <li><strong>housing_project.ipynb</strong> – Jupyter notebook containing data preprocessing, visualization, and price prediction models.</li>
  <li><strong>Power BI .pbix file</strong> – Interactive dashboard for exploring various aspects of the Boston housing dataset.</li>
</ul>

<h2>🚀 Project Objectives</h2>
<ul>
  <li>Understand and analyze the Boston Housing dataset using EDA.</li>
  <li>Build regression models to predict housing prices.</li>
  <li>Visualize trends and relationships using Power BI.</li>
  <li>Provide insights using both statistical and visual analysis.</li>
</ul>

<h2>🧠 Machine Learning Workflow (Jupyter Notebook)</h2>
<p>The notebook (<strong>housing_project.ipynb</strong>) includes a complete pipeline for predictive modeling:</p>

<h3>🔹 Data Preprocessing</h3>
<ul>
  <li>Handling missing values</li>
  <li>Renaming columns for clarity</li>
  <li>Encoding categorical variables (e.g., CHAS)</li>
  <li>Train-test splitting using scikit-learn</li>
</ul>

<h3>🔹 Feature Engineering</h3>
<ul>
  <li><strong>Feature Scaling:</strong> Applied standardization to normalize feature distributions for better model performance.</li>
  <li><strong>Polynomial Features:</strong> Generated additional features using polynomial combinations to capture non-linear relationships.</li>
  <li><strong>L2 Regularization (Ridge Regression):</strong> Used to reduce model complexity and prevent overfitting.</li>
  <li><strong>Cross-Validation:</strong> Employed K-Fold Cross Validation to ensure model generalization and avoid data leakage.</li>
</ul>

<h3>🔹 Models Used</h3>
<ul>
  <li>Linear Regression (Baseline model)</li>
  <li>Ridge Regression with L2 penalty and optimized hyperparameters</li>
</ul>
<p><strong>Evaluation metrics:</strong></p>
<ul>
  <li>R² Score</li>
  <li>Mean Absolute Error (MAE)</li>
</ul>
<p>The models were tuned, validated, and compared to select the best performing configuration for reliable price prediction.</p>

<h2>📊 Power BI Dashboard</h2>
<p>The Power BI dashboard was built to provide a business-oriented perspective of the data and support visual exploration. It includes:</p>

<h3>📈 Page 1:</h3>
<ul>
  <li><strong>KPI Cards:</strong> Max, Min, Average of PRICE and TAX</li>
  <li><strong>Pie Chart:</strong> Distribution of homes based on RAD (accessibility to highways)</li>
  <li><strong>Histogram:</strong> Price distribution across all houses</li>
  <li><strong>Scatter Plots:</strong>
    <ul>
      <li><strong>LSTAT vs PRICE:</strong> Shows a negative correlation between lower economic status and house price</li>
      <li><strong>AGE vs PRICE:</strong> Relationship between age of houses and their prices</li>
      <li><strong>RM vs PRICE:</strong> Strong positive correlation between number of rooms and price</li>
    </ul>
  </li>
</ul>

<h3>📉 Page 2:</h3>
<ul>
  <li><strong>Correlation Heatmap:</strong> Displays relationships between features like LSTAT, RM, PTRATIO,

