# eCommerce Customer Segmentation and Insights

## Overview
This project focuses on analysing customer purchases and transaction data to segment customers based on their similarities. The goal is to identify groups of similar customers, which can help in personalising marketing efforts, improving customer targeting, and enhancing product recommendations.

## Process
1. **Exploratory Data Analysis (EDA):** 
   - EDA is performed using a custom-built EDA class to understand the data.

2. **Similarity Calculation:**
   - The top 3 most similar customers to each customer are identified using cosine similarity, based on customer data like transaction history and purchase history.

3. **Customer Clustering:**
   - Clustering is performed to group similar customers using clustering algorithms, achieving a DB index value of 0.5, indicating well-formed clusters.

## Technologies Used
- Python (Pandas, NumPy, Matplotlib, Seaborn)
- Scikit-learn (for clustering, cosine similarity)
- Custom EDA class for data analysis


