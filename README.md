<h1 align="center">Predicting Diabetes in Pima Indian Women: A Machine Learning Approach</h1>

<br/>

<h2>🚀 <strong>Project Overview</strong></h2>
<p>
This project focuses on building a machine learning model to predict the likelihood of diabetes among Pima Indian women in Phoenix. Using data sourced from the National Institutes of Diabetes-Digestive-Kidney Diseases, we explore features like glucose levels, BMI, and insulin to make predictions that could aid in early detection and intervention.
</p>
<p><em>Dataset available on <a href="https://www.kaggle.com/datasets/uciml/pima-indians-diabetes-database" target="_blank">Kaggle</a>.</em></p>


<h2>📂 <strong>Table of Contents</strong></h2>
<ol>
  <li>Exploratory Data Analysis (EDA)</li>
  <li>Data Preprocessing and Feature Engineering</li>
  <li>Model Development</li>
  <li>Feature Importance</li>
</ol>

<h2>🔍 <strong>1. Exploratory Data Analysis (EDA)</strong></h2>
<p>We begin by exploring the dataset to understand its structure, identify missing values, and analyze patterns in the data.</p>
<ul>
  <li><strong>Data Loading:</strong> The dataset contains 768 entries with 9 columns including features like glucose, blood pressure, and age.</li>
  <li><strong>Data Exploration:</strong> Summary statistics and null value checks revealed no missing values but indicated potential outliers in features such as insulin and skin thickness.</li>
  <li><strong>Age Group Analysis:</strong> Created categorical age groups to analyze patterns across different life stages.</li>
  <li><strong>Outlier Analysis:</strong> Identified and handled outliers using interquartile range thresholds.</li>
</ul>

<h2>⚙️ <strong>2. Data Preprocessing and Feature Engineering</strong></h2>
<ul>
  <li><strong>Handling Missing Values:</strong> Replaced zeros in critical columns with NaN and filled missing values using median values grouped by age categories.</li>
  <li><strong>Feature Engineering:</strong> Created new features like:
    <ul>
      <li>Pregnancy Category</li>
      <li>BMI Category</li>
      <li>Insulin Sensitivity and Resistance Index</li>
      <li>Triceps Skin Fold Thickness Indicator</li>
    </ul>
  </li>
  <li><strong>Encoding and Scaling:</strong> Applied one-hot encoding for categorical features and standardized numerical features using <code>StandardScaler</code>.</li>
</ul>

<h2>🤖 <strong>3. Model Development</strong></h2>
<ul>
  <li><strong>Train-Test Split:</strong> Split the dataset into training (70%) and testing (30%) sets.</li>
  <li><strong>Random Forest Classifier:</strong> Trained a Random Forest model, achieving a reliable accuracy score on the test set.</li>
</ul>

<h2>📊 <strong>4. Feature Importance</strong></h2>
<p>Analyzed the importance of each feature in predicting diabetes using the Random Forest model:</p>
<ul>
  <li><strong>Top Features:</strong> 
    <ul>
      <li>Glucose</li>
      <li>Insulin Resistance Index</li>
      <li>BMI</li>
      <li>Age</li>
      <li>Insulin Sensitivity</li>
    </ul>
  </li>
</ul>
<p>Feature importance analysis provides valuable insights for identifying key health indicators.</p>

<h2>🔧 <strong>Tools & Technologies Used</strong></h2>
<div align="center">
    <img src="https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54" alt="Python"/>
    <img src="https://img.shields.io/badge/pandas-150458?style=for-the-badge&logo=pandas&logoColor=white" alt="Pandas"/>
    <img src="https://img.shields.io/badge/numpy-013243?style=for-the-badge&logo=numpy&logoColor=white" alt="NumPy"/>
    <img src="https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white" alt="Scikit-learn"/>
    <img src="https://img.shields.io/badge/matplotlib-11557C?style=for-the-badge&logo=matplotlib&logoColor=white" alt="Matplotlib"/>
    <img src="https://img.shields.io/badge/seaborn-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Seaborn"/>
</div>

<h2>📈 <strong>Key Insights</strong></h2>
<ul>
  <li>Glucose and Insulin Resistance are the most significant features in predicting diabetes.</li>
  <li>Outlier handling and feature engineering improve model performance.</li>
  <li>Using categorical encodings like BMI and age groups enhances interpretability.</li>
</ul>

<h2>📢 <strong>Contact</strong></h2>
<ul>
  <li><a href="https://www.linkedin.com/in/yourusername/" target="_blank"><img src="https://img.shields.io/badge/LinkedIn-%230077B5.svg?logo=linkedin&logoColor=white" alt="LinkedIn"/></a></li>
  <li><a href="mailto:your.email@example.com"><img src="https://img.shields.io/badge/Email-D14836?logo=gmail&logoColor=white" alt="Email"/></a></li>
</ul>

<p align="center">&copy; 2025 Your Name. All rights reserved.</p>

<hr/>

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=ecembayindir&repo=predicting-diabetes&label=Repository%20views&color=0e75b6&style=flat" alt="Repository Views">
</p>
