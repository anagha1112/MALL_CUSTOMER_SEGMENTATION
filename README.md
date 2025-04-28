# 🛍️ Mall Customer Segmentation using KMeans Clustering

**📚 Project Overview**

This project focuses on segmenting customers of a mall based on their Annual Income and Spending Score, using KMeans Clustering.
The objective is to uncover customer groups with similar characteristics to help businesses tailor their marketing strategies and improve customer engagement.

The dataset is sourced from Kaggle - [Visit Kaggle Mall Dataset](https://www.kaggle.com/datasets/vjchoudhary7/customer-segmentation-tutorial)


**🔍 Problem Statement**

-> Businesses need to identify different customer personas to:

-> Increase customer loyalty,

-> Personalize marketing campaigns,

-> Launch targeted products and services,

-> Maximize profits.

By clustering customers, the mall management can better understand spending behaviors and optimize customer retention strategies.

**📊 Dataset Information**
*Features:*

** *CustomerID* ** — Unique ID for each customer

** *Gender* ** — Male or Female

** *Age* ** — Age of the customer

** *Annual Income (k$)* ** — Annual income in thousands of dollars

** *Spending Score (1–100)* ** — Score assigned based on customer behavior and spending nature

Source: [Kaggle Mall Customer Segmentation Dataset](https://www.kaggle.com/datasets/vjchoudhary7/customer-segmentation-tutorial)

**🛠️ Tools and Technologies Used**

-> Python

-> Pandas — Data manipulation

-> Seaborn & Matplotlib — Data visualization

-> Scikit-learn — Machine Learning (KMeans Clustering)

-> Google Colab — Coding environment

**📈 Approach**

1) Data Exploration:

   -> Loaded and visualized the dataset.

   -> Analyzed the distribution of income and spending scores.

2) Feature Selection:

   -> Selected Annual Income and Spending Score for clustering (2D space).

3) Optimal Cluster Finding:

    -> Used the Elbow Method to determine the ideal number of clusters.

4) KMeans Clustering:

   -> Applied the KMeans algorithm to segment the customers into distinct groups.

5) Visualization:

   -> Plotted clusters using scatter plots to visually differentiate customer segments.

   -> Interpreted clusters to derive actionable business insights.

**🧠 Business Insights**

-> Identified high-income, high-spending premium customers.

-> Detected customers with low spending despite high income (potential targets for marketing).

-> Found loyal customers with modest incomes but high spending scores.

-> Designed segment-specific strategies for marketing, retention, and upselling.

**🚀 How to Run**

-> Clone the repository or download the notebook.

-> Open the .ipynb file in Google Colab or Jupyter Notebook.

-> Install required libraries if missing:


```bash
pip install pandas matplotlib seaborn scikit-learn
```


**📌 Key Outputs**

-> Optimal clusters determined using the Elbow Method.

-> Customer segmentation plotted with spending behavior analysis.

-> Clear interpretation of each cluster and strategic business actions suggested.

**📎 Future Work**

-> Incorporate additional features like Age and Gender for multi-dimensional clustering.

-> Use advanced clustering algorithms like DBSCAN or Hierarchical Clustering.

-> Apply customer lifetime value (CLV) modeling on the clusters.

**🤝 Acknowledgements**

Dataset Source: Kaggle - Customer Segmentation

Inspired by real-world business applications in retail and marketing analytics.

