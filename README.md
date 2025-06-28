## 🎬 IMDB Movie Rating Prediction

This project is part of a Data Science internship task focused on predicting IMDB movie ratings using machine learning techniques. The notebook includes the entire pipeline—from data preprocessing and EDA to model training and evaluation.

---


### 🧠 Project Objective

To build a predictive model that estimates the **IMDB rating** of a movie based on multiple features such as `director`, `cast`, `genre`, `duration`, etc.

---

### 🚀 Technologies Used

* Python 🐍
* Pandas
* NumPy
* Matplotlib & Seaborn
* Scikit-learn
* XGBoost

---

### 📊 Workflow Overview

1. **Data Loading & Exploration**
   Load the dataset and inspect for null values, feature types, and distribution.

2. **Data Cleaning**

   * Remove missing or redundant columns
   * Convert categorical data to numerical using label encoding or one-hot encoding

3. **Exploratory Data Analysis (EDA)**

   * Correlation heatmaps
   * Distribution plots and scatter plots to understand relationships

4. **Feature Selection**

   * Drop low-importance or high-correlation features
   * Choose input variables (independent) and target (`IMDB Rating`)

5. **Model Building & Training**

   * Train/Test split
   * Linear Regression, RandomForest, XGBoost Regressors used
   * Evaluation with R² Score and MAE

6. **Model Evaluation**

   * Compare performance of all models
   * Visualize prediction vs actual results

---

### 📈 Results

* Models trained: **Linear Regression**, **RandomForestRegressor**, **XGBRegressor**
* Best model achieved an **R² Score** of around **0.80+** indicating a fairly strong predictive performance on test data.

---

### 📌 Future Improvements

* Incorporate more robust feature engineering
* Use NLP techniques on plot summaries or reviews
* Deploy as a web app for live prediction

---

### 📚 Acknowledgements

This project was developed as part of the **CodSoft Data Science Internship**.

