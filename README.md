# Marketing-Campaign-Analysis

# Market Campaign Analysis: Customer Segmentation using Clustering Techniques

## Project Overview

In today’s competitive marketing landscape, one-size-fits-all campaigns are inefficient. Businesses must personalize campaigns based on customer behavior, preferences, and demographics to maximize ROI and improve engagement. Customer segmentation using data science techniques allows organizations to identify and target the right audience with tailored messaging and offers.

This project, a capstone-level effort, focuses on clustering customers into actionable segments to guide strategic marketing decisions. The dataset reflects both demographic and behavioral data, making it ideal for testing unsupervised learning approaches in a real-world business context.

## Problem Definition

### Context

Customer segmentation is a core pillar of strategic marketing. Understanding distinct customer personas enables businesses to:
- Anticipate needs and behaviors
- Design highly relevant and personalized campaigns
- Improve customer retention and reduce churn
- Allocate marketing resources effectively

### Objective

The objective of this project is to:
- Identify the most effective clustering algorithm for customer segmentation
- Generate clear and interpretable customer clusters
- Enable marketing teams to design campaign strategies tailored to each group

### Key Questions
- Which clustering algorithms (e.g., K-Means, GMM, DBSCAN, Hierarchical, K-Medoids) provide the most meaningful segmentation?
- How well do the resulting clusters score in terms of cohesion and separation (e.g., using silhouette score)?
- What customer personas emerge from each cluster?
- How actionable are these personas in driving targeted marketing strategies?

### Problem Formulation

This is an **unsupervised learning** problem. The goal is to:
- Discover natural groupings among customers based on demographics and purchase behavior
- Use clustering results to inform personalized marketing
- Translate cluster characteristics into data-driven recommendations

## Dataset Description

The dataset includes both demographic and transactional attributes:

| Column | Description |
|--------|-------------|
| `ID` | Unique customer identifier |
| `Year_Birth` | Year of birth |
| `Education` | Level of education |
| `Marital_Status` | Marital status |
| `Kidhome` | Number of small children |
| `Teenhome` | Number of teenagers |
| `Income` | Household income (USD/year) |
| `Recency` | Days since last purchase |
| `Dt_Customer` | Enrollment date |
| `MntFishProducts` | Spend on fish products (last 2 years) |
| `MntMeatProducts` | Spend on meat products |
| `MntFruits` | Spend on fruits |
| `MntSweetProducts` | Spend on sweet products |
| `MntWines` | Spend on wine products |
| `MntGoldProds` | Spend on gold products |
| `NumDealsPurchases` | Purchases with discount |
| `NumCatalogPurchases` | Purchases via catalog |
| `NumStorePurchases` | In-store purchases |
| `NumWebPurchases` | Web purchases |
| `NumWebVisitsMonth` | Website visits in the last month |
| `AcceptedCmp1-5` | Response to first through fifth campaigns |
| `Response` | Response to most recent campaign |
| `Complain` | Whether the customer filed a complaint |

## Methodology

1. **Data Preprocessing**
   - Handling missing values
   - Feature transformation and encoding
   - Outlier treatment
   - Standardization

2. **Exploratory Data Analysis (EDA)**
   - Distribution analysis
   - Correlation heatmaps
   - Behavioral and demographic profiling

3. **Dimensionality Reduction**
   - PCA for feature compression
   - t-SNE for nonlinear mapping and visualization

4. **Clustering Techniques Evaluated**
   - K-Means
   - Gaussian Mixture Models (GMM)
   - DBSCAN
   - Agglomerative (Hierarchical)
   - K-Medoids

5. **Evaluation Metrics**
   - Silhouette Score
   - Davies-Bouldin Index
   - Cluster interpretability and business usability

## Key Insights

- Clusters revealed clear customer personas (e.g., high-income, wine-lover families vs. discount-sensitive small households).
- K-Means and GMM provided the most stable and interpretable clusters based on silhouette scores.
- Segments varied in purchase behavior, channel preference, and campaign responsiveness.
- Strategic marketing suggestions included product bundling, channel-specific offers, and demographic-based promotions.

## Tech Stack

- Language: Python
- Libraries: Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn, Plotly, t-SNE, PCA
- Notebook: Jupyter Notebook


## How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/market-campaign-analysis.git
   cd market-campaign-analysis
## Install dependencies:
pip install -r requirements.txt

## Launch Jupyter Notebook:
jupyter notebook notebooks/customer_segmentation_analysis.ipynb


##  Final Report

This project explores customer segmentation using unsupervised learning algorithms such as K-Means, GMM, DBSCAN, and Hierarchical Clustering. The objective is to identify actionable customer personas based on demographic and behavioral features to enable data-driven marketing strategies.

The full report includes:
- Detailed comparison of clustering techniques
- Evaluation metrics (e.g., silhouette score)
- Key business insights and personas
- Strategic marketing recommendations
- Risks, costs, and future enhancements

 [View Final HTML Report](https://harishvo6.github.io/Marketing-Campaign-Analysis/)


