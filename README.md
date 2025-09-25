# Customer Segmentation using K-Means Clustering
![Customer Segmentation](https://img.shields.io/badge/ML-Clustering-blue)  
![KMeans](https://img.shields.io/badge/Algorithm-KMeans-orange)  
![Google Colab](https://img.shields.io/badge/Platform-Google%20Colab-yellow)  
![Python](https://img.shields.io/badge/Language-Python-green)  


##  Project Overview
This project focuses on **customer segmentation** using machine learning techniques.  
The goal is to group customers into different clusters based on their **purchasing behavior** (Annual Income & Spending Score) and extract meaningful insights that businesses can use for **targeted marketing, personalized offers, and strategic decision-making**.

This project was implemented in **Google Colab** for ease of use, reproducibility, and interactive analysis.  [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/SharonneKemboi/Customer-Segmentation-Analysis/blob/master/Customer_Segmentation.ipynb)

>  Special thanks to **Arch Technologies** for the opportunity to learn and engage in such a project.  
##  Objectives
The main goals of this project are:
1. Perform **Exploratory Data Analysis (EDA)** on customer data.  
2. Handle **missing values** and clean data for better analysis.  
3. Transform categorical variables for compatibility with ML algorithms.  
4. Apply **K-Means clustering** for customer segmentation.  
5. Use the **Elbow Method** to find the optimal number of clusters.  
6. Visualize and interpret results to provide **actionable business insights**.  

## Features of This Project
- Clean, well-documented **Google Colab notebook**  
- Beautiful visualizations with seaborn & matplotlib  
- Handles **missing values & outliers** effectively  
- Step-by-step **EDA with plots & tables**  
- Cluster visualization in **2D & 3D**  
- Easy to follow for **students, teachers, and professionals**  

## Dataset
The dataset contains **200 customers** with the following features:

| Column Name              | Description                                |
|---------------------------|--------------------------------------------|
| `CustomerID`             | Unique ID assigned to each customer        |
| `Genre`                  | Gender of the customer (Male/Female)       |
| `Age`                    | Age of the customer                       |
| `Annual Income (k$)`     | Annual income of the customer in $1000s    |
| `Spending Score (1-100)` | Score assigned based on purchasing habits  |

## Exploratory Data Analysis (EDA)
We explored the dataset through:
- Descriptive statistics (mean, median, etc.)  
- Distribution plots of Age, Income, and Spending Score  
- Boxplots to identify outliers  
- Correlation heatmaps for feature relationships  
- Pairplots to explore feature interactions  

## Machine Learning: K-Means Clustering
###  Steps:
1. **Preprocessing** – Handle missing values, label encode `Genre`, and scale numerical features.  
2. **Choosing features** – Focus on `Annual Income` and `Spending Score` for clustering.  
3. **Elbow Method** – Determine optimal clusters (usually 5).  
4. **Apply K-Means** – Segment customers into groups.  
5. **Visualization** – Scatter plots and cluster centroids.  

## Results & Insights
The clustering produced **5 distinct customer segments**:
1. **High Income – Low Spending** → Potential customers (need targeted offers).  
2. **High Income – High Spending** → VIP customers (loyal, high-value).  
3. **Low Income – High Spending** → Price-sensitive but frequent shoppers.  
4. **Low Income – Low Spending** → Less engaged customers.  
5. **Middle Income – Moderate Spending** → Average group with moderate potential.  

**Business Value**: These insights help businesses design **personalized marketing strategies** like targeted promotions, loyalty programs, and efficient resource allocation.  
## Visualizations
Here are some example visualizations used in the project:

- Distribution of Annual Income & Spending Score
- Heatmap of Correlations  
- Elbow Method Curve  
- Cluster Visualization (2D Scatter & 3D Plot) 

You can run and view all visuals in the Colab notebook.

##  How to Use This Project
###  Option 1: Run on Google Colab (Recommended )
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/SharonneKemboi/Customer-Segmentation-Analysis/blob/master/Customer_Segmentation.ipynb)

###  Option 2: Run Locally
1. Clone this repo  
   ```bash
   git clone https://github.com/SharonneKemboi/Customer-Segmentation-Analysis.git
   cd Customer-Segmentation-Analysis
Install requirements

Copy code
>>
 pip install -r requirements.txt
 Run Jupyter Notebook or any IDE.


## Conclusion
1. K-Means successfully segmented customers into 5 actionable groups.
2. The Elbow Method helped determine the optimal cluster count.


## Acknowledgments
 > Special thanks to Arch Technology for the opportunity to learn and engage in such a project.
 > Gratitude to the open-source community for datasets and libraries.

## License
  > This project is licensed under the MIT License – feel free to use, modify, and share with attribution.

- Feel free to open issues or contribute via pull requests.

### Connect
Author: Sharonne Kemboi
Location: Nairobi, Kenya
Interests: Data Science | AI | Machine Learning | Deep Learning |Data Analytics

[LinkedIn](https://www.linkedin.com/in/sharonne-kemboi/) | [GitHub](https://github/SharonneKemboi/)

