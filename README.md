# Customer Segmentation using K-Means Clustering

##  Project Overview
This project focuses on **customer segmentation** using machine learning techniques.  
The goal is to group customers into different clusters based on their **purchasing behavior** (Annual Income & Spending Score) and extract meaningful insights that businesses can use for **targeted marketing, personalized offers, and strategic decision-making**.

This project was implemented in **Google Colab** for ease of use, reproducibility, and interactive analysis.  

>  Special thanks to **Arch Technologies** for the opportunity to learn and engage in such a project.  

---

##  Run the Project
Click below to open the notebook directly in **Google Colab**:

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/SharonneKemboi/Customer-Segmentation-Analysis/blob/master/Customer_Segmentation.ipynb)

---

##  Tech Stack & Dependencies
The project is built using **Python** and popular ML/data science libraries:

- **pandas** → data manipulation  
- **numpy** → numerical computations  
- **matplotlib & seaborn** → static visualizations  
- **plotly** → interactive plots  
- **scikit-learn** → clustering (KMeans), scaling, evaluation metrics  
- **missingno** → missing values visualization  

---

##  Dataset
- **File**: `Mall_Customers.csv`  
- **Columns**:
  - `CustomerID`
  - `Genre`
  - `Age`
  - `Annual Income (k$)`
  - `Spending Score (1-100)`

---

##  Exploratory Data Analysis (EDA)

### 1. Data Preview
```python
df.head()
