# Customer Segmentation & Retention Analysis

## Overview

This project applies data analytics and machine learning techniques to segment customers into meaningful groups based on income, spending behavior, and household composition. The goal is to enable **data-driven marketing decisions**, improve **customer retention**, and maximize **return on marketing spend**.

Rather than treating all customers uniformly, this analysis identifies **who the customers are, how they behave, and where the business should focus its efforts**.

---

## Business Problem

Generic marketing campaigns are expensive and inefficient. Without understanding customer heterogeneity, businesses risk:
- Overspending on low-value customers  
- Under-engaging high-value segments  
- Poor campaign conversion rates  

This project solves that by transforming raw customer data into **actionable customer personas**.

---

## Key Objectives

- Segment customers into behaviorally distinct groups  
- Analyze spending patterns across product categories  
- Identify high-value and high-risk customer segments  
- Provide clear, practical marketing recommendations  

---

## Customer Segments Identified

Using unsupervised clustering, three core customer personas emerged:

### 1. Wealthy Non-Parents (Cluster 1)
- **Profile**: High income, high discretionary spending, no children  
- **Behavior**: Frequent buyers of premium products (wine, meat)  
- **Business Value**: Highest revenue per customer  
- **Strategy**: Loyalty programs, premium launches, exclusivity-driven campaigns  

### 2. Affluent Parents (Cluster 2)
- **Profile**: High income households with children  
- **Behavior**: Strong overall spend, driven by family needs  
- **Business Value**: High lifetime value with expansion potential  
- **Strategy**: Family bundles, convenience-focused offers, cross-category upselling  

### 3. Budget-Conscious Parents (Cluster 0)
- **Profile**: Lower income, price-sensitive households  
- **Behavior**: Promotion-driven purchasing behavior  
- **Business Value**: Low margin, high volume  
- **Strategy**: Discount-based targeting during sales cycles only  

---

## Methodology

### Data Preparation
- Removed outliers and handled missing values  
- Standardized numerical features to ensure clustering accuracy  

### Feature Engineering
- Created aggregate metrics such as **Total Spending** and **Customer Age**  
- Transformed raw attributes into behavior-focused indicators  

### Dimensionality Reduction
- Applied **Principal Component Analysis (PCA)** to reduce noise  
- Enabled effective visualization of customer clusters  

### Clustering
- Used **Agglomerative Hierarchical Clustering**  
- Grouped customers based on similarity across income, spending, and household features  

---

## Business Recommendations

- **Retention Priority**: Focus on Wealthy Non-Parents due to highest ROI  
- **Growth Lever**: Increase basket size of Affluent Parents via tailored bundles  
- **Cost Control**: Limit marketing spend on Budget-Conscious Parents to discount periods  

This targeted approach reduces wasted spend while improving campaign effectiveness.

---

## Tech Stack

- **Programming**: Python  
- **Data Analysis**: Pandas, NumPy  
- **Machine Learning**: Scikit-learn (PCA, Clustering)  
- **Visualization**: Matplotlib, Seaborn  

---

## Outcome

The project demonstrates how unsupervised learning can translate raw customer data into **clear business strategy**, bridging the gap between analytics and decision-making.
