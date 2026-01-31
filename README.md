# Customer Segmentation & Retention Analysis

## Project Overview
This project leverages advanced data analytics and machine learning to segment a customer base into distinct groups. By understanding the unique behaviors, spending habits, and demographic profiles of these segments, the business can optimize marketing spend, improve customer retention, and personalize promotional offers.

## Key Objectives
*   **Identify Customer Personas**: Group customers based on shared characteristics.
*   **Analyze Spending Behavior**: Understand who spends the most and on what products.
*   **Optimize Campaign Strategy**: Determine which segments are most responsive to promotions.

## The Data-Driven Personas
Through clustering analysis, we identified three primary customer segments:

1.  **Wealthy Non-Parents** (Cluster 1)
    *   **Profile**: High income, high spending, no children in the household.
    *   **Behavior**: Most frequent purchasers of premium products like wine and meat.
    *   **Opportunity**: High-value loyalty programs and luxury product launches.

2.  **Affluent Parents** (Cluster 2)
    *   **Profile**: High income, high spending, but with children.
    *   **Behavior**: Significant spending power but likely driven by family needs.
    *   **Opportunity**: Family-oriented premium bundles and convenience-based services.

3.  **Budget-Conscious Parents** (Cluster 0)
    *   **Profile**: Lower income and lower spending, primarily parents.
    *   **Behavior**: Responsive to deals and price-sensitive.
    *   **Opportunity**: Targeted discounts, 'deal' notifications, and value-based marketing.

## Methodology (Simplified)
*   **Data Cleaning**: Removed outliers and handled missing information to ensure accuracy.
*   **Feature Engineering**: Created new metrics like 'Total Spent' and 'Customer Age' to get a deeper look at behavior.
*   **Dimensionality Reduction (PCA)**: Simplified complex data into 3 key components to visualize the 'Big Picture'.
*   **Clustering (Agglomerative)**: Grouped customers mathematically based on similarities in income, spending, and family size.

## Business Recommendations
*   **Retention**: Focus on the 'Wealthy Non-Parents' segment as they represent the highest ROI per customer.
*   **Growth**: Design specific 'Family-First' campaigns for 'Affluent Parents' to increase their basket size in non-staple categories.
*   **Efficiency**: Reduce broad-spectrum marketing and instead target the 'Budget-Conscious' group only during major sale events or with discount-focused deals.

## Tech Stack
*   **Analysis**: Python, Pandas, NumPy
*   **Machine Learning**: Scikit-Learn (PCA, Clustering)
*   **Visualization**: Matplotlib, Seaborn
