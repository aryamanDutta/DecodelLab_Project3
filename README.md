# Customer Segmentation Analysis using PCA & K-Means Clustering

## Project Overview

This project focuses on customer segmentation using unsupervised machine learning techniques. The objective is to identify distinct customer groups based on purchasing behavior, demographic characteristics, and campaign interactions.

Principal Component Analysis (PCA) was used for dimensionality reduction, followed by K-Means Clustering for customer segmentation. The results were visualized using Power BI to generate actionable business insights.

---

## Objectives

* Perform customer segmentation using clustering techniques.
* Reduce dimensionality using PCA while preserving data variance.
* Determine the optimal number of clusters using the Elbow Method and Silhouette Analysis.
* Identify meaningful customer personas.
* Create an interactive dashboard to visualize customer segments and spending patterns.

---

## Dataset

**Dataset:** Marketing Campaign Dataset

The dataset contains customer demographic information, purchasing behavior, spending patterns, and campaign responses.

Key attributes include:

* Income
* Age
* Marital Status
* Education
* Product Spending Categories
* Store Purchases
* Web Purchases
* Catalog Purchases
* Campaign Responses

---

## Project Workflow

### 1. Data Preprocessing

* Handled missing values in the Income column.
* Removed unnecessary identifiers and metadata columns.
* Performed feature engineering by creating Age from Year_Birth.
* Applied one-hot encoding to categorical variables.

### 2. Feature Scaling

* Standardized numerical features using StandardScaler.

### 3. Principal Component Analysis (PCA)

* Applied PCA to reduce dimensionality.
* Preserved 95% of cumulative variance.
* Reduced the dataset from 35 features to 27 principal components.

### 4. Clustering

* Implemented K-Means Clustering.
* Evaluated cluster quality using:

  * Elbow Method
  * Silhouette Score

### 5. Customer Profiling

Generated customer personas based on:

* Income
* Spending behavior
* Purchase channels
* Product preferences

### 6. Dashboard Development

Created a Power BI dashboard to visualize:

* Customer Distribution by Cluster
* Average Income by Cluster
* Average Total Spending by Cluster
* Average Wine Spending by Cluster

---

## Customer Personas

### Cluster 0 – Low-Value At-Risk Customers

* Lowest income and spending levels.
* Limited purchasing activity.
* Require retention and engagement strategies.

### Cluster 1 – Budget-Conscious Shoppers

* Moderate purchasing activity.
* Price-sensitive customers.
* Suitable for discounts and loyalty programs.

### Cluster 2 – Mature Value Buyers

* Older customer segment.
* Moderate income and spending patterns.
* Respond well to targeted promotions.

### Cluster 3 – Premium Loyal Customers

* High spending and strong engagement.
* Frequent purchasers across channels.
* Ideal candidates for loyalty rewards.

### Cluster 4 – Elite High-Value Customers

* Highest income and spending levels.
* Strong preference for premium products.
* Valuable segment for personalized marketing campaigns.

---

## Power BI Dashboard

The dashboard provides an executive overview of customer segmentation results through:

* KPI Cards
* Customer Distribution Analysis
* Spending Analysis
* Income Analysis
* Product Preference Analysis

---

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Jupyter Notebook
* Power BI

---

## Project Structure

```text
DecodelLab_Project3/
│
├── data/
│   └── marketing_campaign.csv
│
├── notebooks/
│   └── Customer_Segmentation.ipynb
│
├── outputs/
│   ├── customer_segments.csv
│   └── cluster_profiles.csv
│
├── dashboard/
│   ├── Customer_Segmentation_Dashboard.pbix
│   └── dashboard_screenshot.png
│
├── README.md
├── requirements.txt
└── .gitignore
```

---

## Results

* Successfully segmented customers into 5 meaningful groups.
* Reduced dimensionality while preserving 95% variance.
* Identified high-value and low-value customer segments.
* Generated actionable business insights for targeted marketing strategies.
* Developed a Power BI dashboard for business decision-making.

---

## Author

Aryaman Dutta

Data Science & Analytics Internship Project
