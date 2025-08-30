# SKODA-Used-Car-Analysis
Predicting resale prices of Skoda used cars through data analysis and machine learning.

### Project Overview

This project focuses on **data visualization, data analysis, and machine learning** applied to a **Škoda used car dataset**.

**Objective:**  
Build a machine learning model to **predict the resale price of Škoda used cars** with minimal error and evaluate its performance using key performance indicators (KPIs).

---

### Methodology

#### 1. Exploratory Data Analysis (EDA)

* Loaded the dataset into a **Pandas DataFrame**.
* Checked **data types** and **missing values**.
* Examined the **distribution of manufacturing years**.
* Preprocessed the data for visualization.
* Performed visual analyses including:
  * **Bar plots** for categorical features
  * **Scatter plots with trendlines** for correlations
  * **Histograms** and **distribution plots** for numerical features
  * **Boxplots** and **violin plots** to identify spread and outliers
  * Comparative plots based on **mode, transmission, and fuel type**

#### 2. Machine Learning Model

* Implemented **Linear Regression** for price prediction.

**Preprocessing Steps:**

* Applied **One-Hot Encoding** for categorical variables
* Applied **Label Encoding** where needed

**Model Evaluation (KPIs):**

* **Mean Absolute Error (MAE)**
* **Mean Squared Error (MSE)**
* **Root Mean Squared Error (RMSE)**
* **R-squared (R²)**

**Prediction Analysis:**

* Compared **actual vs. predicted resale prices** using a **scatter plot**.

