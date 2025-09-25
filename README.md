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


##  Tech Stack & Dependencies
The project is built using **Python** and popular ML/data science libraries:

##  Tools & Libraries
- pandas & numpy** → data cleaning & manipulation  
- matplotlib, seaborn & plotly** → data visualization  
- scikit-learn** → K-Means clustering, scaling, evaluation metrics  
- missingno** → missing values visualization  


##  Dataset
- **File**: `Mall_Customers.csv`  


##  Exploratory Data Analysis (EDA)
I managed to perform the following EDA to better understand the dataset:

- Data Overview & Summary Statistics  
- Missing Values Check** (visualized with `missingno`)  
- Feature Distributions** (Age, Income, Spending Score)  
- Correlation Heatmap** to explore relationships between numerical features  

*Visual Examples:*  
![Data Preview](images/data_preview.png)  
![Distributions](images/distributions.png)  
![Correlation Heatmap](images/correlation_heatmap.png)  



##  Preprocessing
- Removed missing values  
- Encoded categorical variables (`Genre`)  
- Scaled numerical features for clustering  


##  Clustering
- Applied the **Elbow Method** and **Silhouette Score** to identify the optimal number of clusters  
- Selected **5 clusters** for segmentation  
- Built the **K-Means model** and assigned each customer to a cluster  

*Visual Examples:*  
![Elbow Method](images/elbow_method.png)  
![Clusters](images/clusters.png)  


##  Results & Insights

### Cluster Profiles
| Cluster | Avg Age | Avg Income | Avg Spending Score | Segment Insight |
|---------|----------|-------------|----------------------|-----------------|
| 0 | ... | ... | ... | High Income, High Spending → Premium Customers  |
| 1 | ... | ... | ... | Low Income, Low Spending → Not Engaged  |
| 2 | ... | ... | ... | High Income, Low Spending → Upsell Opportunity  |
| 3 | ... | ... | ... | Low Income, High Spending → Budget Loyalists  |
| 4 | ... | ... | ... | Middle Class, Moderate Spending → Growth Segment  |

*Cluster Analysis Visuals:*  
![Cluster Profiles](images/cluster_profiles.png)  
![Pairplot](images/pairplot.png)  



##  Insights
- **Cluster 0 (Premium Customers):** High potential for **exclusive offers**  
- **Cluster 1 (Not Engaged):** Focus on **re-engagement strategies**  
- **Cluster 2 (Upsell Opportunity):** Encourage higher spending through **premium packages**  
- **Cluster 3 (Budget Loyalists):** Maintain loyalty with **discount-driven campaigns**  
- **Cluster 4 (Growth Segment):** Represent **middle-income customers** who could grow into premium  

##  Conclusion
- Successfully segmented customers into **5 distinct groups**  
- Provided insights that can help businesses design **personalized marketing strategies**  
- Suggested future improvements:
  - Add more features (purchase history, frequency, product categories)  
  - Experiment with alternative clustering algorithms (Agglomerative, DBSCAN)  
  - Validate with cross-industry datasets  


##  Acknowledgements
- Implemented in **Google Colab**  
- Special thanks to **Arch Technologies** for providing the opportunity to learn, explore, and engage in this project.

---
Author

Sharon Kemboi
📍 Nairobi, Kenya
Data & Business Analyst | AI & Data Enthusiast

