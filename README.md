# Machine Learning–Driven Customer Segmentation for Marketing ROI Optimization

## Overview

This project applies machine learning and data analytics to segment customers into actionable groups based on income, spending behavior, and household characteristics. The objective is to help businesses **optimize marketing ROI**, improve **customer retention**, and move away from inefficient one-size-fits-all campaigns.

The analysis demonstrates how raw customer data can be transformed into **clear, business-ready insights** that support strategic marketing decisions.

---

## Business Problem

Traditional marketing strategies often fail because they treat all customers equally. This leads to:

- Overspending on low-value customers  
- Underutilization of high-value segments  
- Low campaign conversion and retention rates  

This project addresses these issues by identifying **behaviorally distinct customer segments** and mapping them directly to **targeted marketing strategies**.

---

## Project Objectives

- Segment customers using unsupervised machine learning  
- Analyze spending behavior across key product categories  
- Identify high-value, growth, and price-sensitive customer groups  
- Translate analytical results into actionable business recommendations  

---

## Customer Segments Identified

Using clustering techniques, three primary customer personas were identified:

### 1. Wealthy Non-Parents (Cluster 1)
- **Profile**: High income, high discretionary spending, no children  
- **Behavior**: Frequent purchases of premium products (e.g., wine, meat)  
- **Business Value**: Highest revenue per customer  
- **Recommended Strategy**: Loyalty programs, premium product launches, exclusivity-based offers  

### 2. Affluent Parents (Cluster 2)
- **Profile**: High-income households with children  
- **Behavior**: Strong overall spending driven by family needs  
- **Business Value**: High lifetime value with growth potential  
- **Recommended Strategy**: Family-oriented bundles, convenience-focused promotions, cross-category upselling  

### 3. Budget-Conscious Parents (Cluster 0)
- **Profile**: Lower income, price-sensitive households  
- **Behavior**: Promotion-driven purchasing behavior  
- **Business Value**: Lower margins, high volume  
- **Recommended Strategy**: Discount-based targeting during major sales events  

---

## Methodology

### Data Preparation
- Removed outliers and handled missing values  
- Standardized numerical features to ensure unbiased clustering  

### Feature Engineering
- Created derived metrics such as **Total Spending** and **Customer Age**  
- Converted raw attributes into behavior-focused indicators  

### Dimensionality Reduction
- Applied **Principal Component Analysis (PCA)** to reduce noise  
- Improved cluster separation and visualization  

### Clustering
- Implemented **Agglomerative Hierarchical Clustering**  
- Grouped customers based on similarity in income, spending, and household features  

---

## Business Recommendations

- **Retention Focus**: Prioritize Wealthy Non-Parents due to highest ROI  
- **Growth Opportunity**: Increase basket size among Affluent Parents using tailored bundles  
- **Cost Efficiency**: Limit broad marketing spend on Budget-Conscious Parents and focus on discount cycles  

This targeted approach improves campaign efficiency while reducing unnecessary marketing costs.

---

## Tech Stack

- **Programming**: Python  
- **Data Analysis**: Pandas, NumPy  
- **Machine Learning**: Scikit-learn (PCA, Clustering)  
- **Visualization**: Matplotlib, Seaborn  

---

## Outcome

This project demonstrates the practical application of unsupervised machine learning to solve real-world business problems by bridging the gap between **data analysis and strategic decision-making**.
