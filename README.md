# E-commerce Customer Segmentation Project

## Project Overview
This project demonstrates advanced data analysis and machine learning techniques to perform customer segmentation for an e-commerce business. Using a real-world dataset containing over 950,000 transactions from a global e-commerce platform, I applied various data science methodologies to derive actionable insights for improving marketing strategies.

## Business Context
The dataset includes customer transactions from five continents and 47 countries, spanning from January 2012 to December 2016. It contains rich information about customers (location, loyalty status) and their orders (delivery times, costs, profits). The goal is to segment customers effectively to enhance marketing efforts and customer engagement.

## Key Features
- Data cleaning and preprocessing of a large, real-world dataset
- Feature engineering to create meaningful customer attributes
- Exploratory Data Analysis (EDA) with visualizations
- Application of clustering algorithms (K-means, Hierarchical Clustering)
- Dimensionality reduction techniques (PCA, t-SNE)
- Determination of optimal cluster numbers using statistical methods
- Visualization of customer segments

## Technical Skills Demonstrated
- Python programming (Pandas, NumPy, Scikit-learn)
- Data preprocessing and feature engineering
- Machine Learning model implementation
- Data visualization (Matplotlib, Seaborn)
- Statistical analysis
- Dimensionality reduction techniques
- Clustering algorithms

## Project Structure
1. Data Import and Preprocessing
2. Feature Engineering
3. Exploratory Data Analysis
4. Clustering Model Implementation
5. Dimensionality Reduction
6. Results Visualization and Interpretation

## Key Findings
Once it was found that the optimal cluster number was 3, k-means was applied to the dataset and the below feature distributions could be observed within clusers: 

![image](https://github.com/user-attachments/assets/383364e2-5f36-4b0e-ace8-11b6be5fe803)

To beter visualise the clusters, PCA was undertaken and then the results plotted: 

![image](https://github.com/user-attachments/assets/5462933a-9c78-4a29-a156-8cc4eb4dfbca)

Together, the following cluster interpretations could be determined: 

# Customer Segmentation Insights and Marketing Strategies

## Cluster Analysis Results

**Cluster 1: Young, Low-Value Customers**
- Characteristics: Younger demographic, low purchase frequency, less recent engagement, lower spending per unit
- Key Marketing Activities:
  1. Implement targeted reactivation campaigns to re-engage these customers
  2. Develop promotions focusing on accessible, low unit-cost products to encourage more frequent purchases
  3. Utilize social media and digital channels popular among younger demographics for marketing outreach
  4. Create loyalty programs with easily attainable initial rewards to boost engagement
  5. Offer personalized product recommendations based on past purchases to increase relevance

**Cluster 2: Middle-Aged, Moderate-Value Customers**
- Characteristics: Middle-aged, moderate purchase frequency, recent engagement, moderate to high spending per unit
- Key Marketing Activities:
  1. Implement upselling and cross-selling strategies to increase customer lifetime value
  2. Develop targeted email campaigns showcasing mid-range to premium products
  3. Create bundle offers combining frequently purchased items with new, complementary products
  4. Implement a tiered loyalty program to encourage increased spending and engagement
  5. Utilize personalized content marketing to educate customers about higher-value products and services

**Cluster 3: Older, High Unit-Cost, Low-Engagement Customers**
- Characteristics: Older demographic, lower engagement frequency, less recent activity, higher spending per unit
- Key Marketing Activities:
  1. Develop a win-back campaign focusing on the unique value proposition for premium products
  2. Create exclusive, personalized offers for high-value items to re-engage these customers
  3. Implement a VIP program with concierge services and early access to new premium products
  4. Utilize traditional marketing channels (e.g., direct mail) alongside digital methods for outreach
  5. Develop content marketing strategies focusing on the quality and longevity of premium products

## Future Work
- Implement more advanced clustering techniques (e.g., DBSCAN, Gaussian Mixture Models)
- Develop a customer lifetime value prediction model
- Create an interactive dashboard for exploring customer segments

## Tools Used
- Python 
- Jupyter Notebook
- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn

## About Me
I'm a data analyst transitioning into data science, passionate about leveraging data to drive business decisions. This project showcases my ability to handle complex datasets, apply machine learning techniques, and derive actionable insights.

Feel free to reach out if you have any questions or would like to discuss this project further!
