# Customer Segmentation using K-Means Clustering
![Customer Segmentation](https://img.shields.io/badge/ML-Clustering-blue)  
![KMeans](https://img.shields.io/badge/Algorithm-KMeans-orange)  
![Google Colab](https://img.shields.io/badge/Platform-Google%20Colab-yellow)  
![Python](https://img.shields.io/badge/Language-Python-green)  
![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-1.1+-orange.svg)
![License](https://img.shields.io/badge/License-MIT-green.svg)
![Colab](https://img.shields.io/badge/Google%20Colab-Compatible-yellow.svg)
![Maintenance](https://img.shields.io/badge/Maintained-Yes-brightgreen.svg)


##  Project Overview
This project focuses on **customer segmentation** using machine learning techniques.  
The goal is to group customers into different clusters based on their **purchasing behavior** (Annual Income & Spending Score) and extract meaningful insights that businesses can use for **targeted marketing, personalized offers, and strategic decision-making**.

This project was implemented in **Google Colab** for ease of use, reproducibility, and interactive analysis.  [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/SharonneKemboi/Customer-Segmentation-Analysis/blob/master/Customer_Segmentation.ipynb)
![Clusters](CLUSTERS.PNG)

>  Special thanks to **Arch Technologies** for the opportunity to learn and engage in such a project.  
###  Key Objectives

* **Data Cleaning**: Handle missing values and remove outliers  
* **EDA**: Understand customer demographics and spending behavior  
* **Feature Transformation**: Encode categorical variables & scale features  
* **Clustering**: Apply **K-Means** to group customers  
* **Optimal Clusters**: Use **Elbow Method** to determine `k`  
* **Visualization**: Present results with clear, engaging plots  
* **Insights**: Derive actionable marketing recommendations  

---

##  Features

1. Perform **complete exploratory data analysis (EDA)** with plots and insights  
2. Encode categorical features (`Genre`) for ML algorithms  
3. Scale numerical features for clustering stability  
4. Use **Elbow Method** to determine optimal clusters  
5. Segment customers into distinct groups with K-Means  
6. Visualize clusters in **2D and 3D scatter plots**  
7. Provide **business-level profiling** of customer groups  

---

##  Dataset

The dataset (`customers.csv`) contains **200 mall customers** with the following features:

| Column | Description |
|--------|-------------|
| `CustomerID` | Unique identifier |
| `Genre` | Gender (Male/Female) |
| `Age` | Age of customer |
| `Annual Income (k$)` | Annual income in thousands |
| `Spending Score (1–100)` | Customer behavior score |

---

##  How to Run

### Option 1: Google Colab (Recommended 🚀)
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/SharonneKemboi/Customer-Segmentation-Analysis/blob/master/Customer_Segmentation.ipynb)

1. Click the button above  
2. Run cells sequentially in Colab  
3. View interactive visualizations  

### Option 2: Local Setup
```bash
git clone https://github.com/SharonneKemboi/Customer-Segmentation-Analysis.git
cd Customer-Segmentation-Analysis
pip install -r requirements.txt
jupyter notebook Customer_Segmentation.ipynb
``` 

## Dependencies
```bashpandas>=1.5.0
numpy>=1.21.0
matplotlib>=3.5.0
seaborn>=0.12.0
scikit-learn>=1.1.0
plotly>=5.0.0
```
```bash
graph TD
    A[ Data Import ] --> B[ Data Cleaning & Missing Values ]
    B --> C[ Exploratory Data Analysis ]
    C --> D[ Preprocessing: Encoding + Scaling ]
    D --> E[ Elbow Method ]
    E --> F[ K-Means Clustering ]
    F --> G[ Visualization ]
    G --> H[ Profiling & Insights ]
```
## Exploratory Data Analysis (EDA)

- Distribution of Age, Income, and Spending Scores  
- Gender-based analysis of income and spending  
- Correlation heatmaps and pairplots  
- Outlier detection with boxplots  

---

##  Clustering & Results

### Elbow Method
The Elbow Method showed that **k=5** was the optimal number of clusters.

### K-Means Clustering
Customers were segmented into 5 groups:

- **Low Income, Low Spending** → Least engaged customers  
- **High Income, High Spending** → VIP customers (high value)  
- **High Income, Low Spending** → Potential but not engaged  
- **Low Income, High Spending** → Price-conscious but active  
- **Middle Income, Moderate Spending** → Average customers  

---

##  Business Insights

-  **Target Segment**: High-income & high-spending customers → ideal for loyalty programs  
-  **Retention Risk**: High-income but low-spending cluster → needs better engagement strategies  
-  **Promotions**: Low-income but high-spending customers → respond well to discounts/offers  

---

##  Visualization Gallery

The notebook produces professional-quality visuals:

- Distribution plots of income/spending  
- Gender vs. spending bar plots  
- Elbow curve for cluster selection  
- 2D and 3D cluster scatter plots  
- Correlation heatmaps  

---

##  Key Learning Outcomes

After completing this project, I have learnt:

- How to perform end-to-end EDA with pandas, seaborn, matplotlib  
- How to Handle categorical and numerical variables in ML workflows  
- How to Apply and Interpret K-Means Clustering  
- How to use the Elbow Method for optimal clusters  
- How to translate clustering results into business strategies  

---

##  Disclaimers & Limitations

- Clustering is unsupervised → requires interpretation  
- Dataset is synthetic mall data → not real-world sales  
- Results depend on chosen features (Income & Spending Score)  
- More dimensions (e.g., transaction history) could yield richer insights  

---

##  Contributing

Contributions are welcome!

- Submit issues for bugs or suggestions  
- Fork and create PRs for new features or visualizations  

### Possible Extensions
- Add Agglomerative / DBSCAN clustering  
- Use PCA for dimensionality reduction  
- Create interactive dashboards with Plotly/Dash  

---

##  License

This project is licensed under the **MIT License** – see the [LICENSE](LICENSE) file for details.  

---

##  Acknowledgments

- **Arch Technologies** for the opportunity to learn and engage in this project  
- **Open Source Community** for datasets, libraries, and tools  
- **Seaborn & Matplotlib teams** for visualization libraries  

---

<div align="center">

 If you found this project useful, don’t forget to **star this repository!**   

Author: Sharonne Kemboi

Location: Nairobi, Kenya

*Interests: Data Science | AI | Machine Learning | Deep Learning |Data Analytics.*  
</div>





[LinkedIn](https://www.linkedin.com/in/sharonne-kemboi/) | [GitHub](https://github/SharonneKemboi/)

