# K-Means Clustering: Age & Income Segmentation

## Project Objective

The objective of this project is to perform an exploratory data analysis by creating clusters based on the variables Age and Income using the K-Means algorithm. The dataset used in this project was obtained from Kaggle.

## Data Quality Analysis

- No missing values were found in the dataset  
- No duplicate records were identified  

This ensures a clean dataset, allowing reliable modeling and analysis.

## Elbow Method Analysis

The Elbow Method was applied to determine the optimal number of clusters.

- Ideal number of clusters identified: 5  
- This point represents where the curve begins to stabilize, indicating diminishing returns in variance reduction.

## Model Evaluation

The clustering performance was evaluated using three key metrics:

### Silhouette Score
- Value: 0.54  
- Interpretation: Indicates good cluster separation (ranges from -1 to 1)

### Davies-Bouldin Index
- Value: 0.52  
- Interpretation: Low value suggests well-separated and compact clusters

### Calinski-Harabasz Index
- Value: 5316  
- Interpretation: High value indicates strong cluster definition  

## Statistical Analysis (ANOVA)

An ANOVA F-test was conducted to evaluate the significance of the variables:

- p-value < 0.05 → Statistically significant differences between clusters  
- Income shows greater differentiation across clusters compared to Age  

This means that Income better characterizes the cluster separation, rather than necessarily having a greater influence on cluster formation.

## Analysis and Business Decision

The clustering results indicate the presence of 5 well-defined customer segments based on Age and Income, supported by strong evaluation metrics and statistical significance.

### Business Decisions

- Deploy the clustering model to segment customers into distinct groups for strategic decision-making  

- Use clusters to personalize business strategies:
  - High income clusters → premium products and investment-focused offerings  
  - Mid income clusters → balanced product portfolios  
  - Lower income clusters → cost-sensitive products and promotions  

### Strategic Applications

- Marketing optimization:
  - Targeted campaigns based on customer segment profiles  
  - Increased conversion rates through personalization  

- Customer experience:
  - Tailored communication and offers  
  - Improved customer engagement and retention  

### Monitoring Strategy

- Continuously monitor cluster distribution over time to detect behavioral shifts:
  - Changes in income distribution  
  - Migration between clusters  
  - Emerging new patterns  

This ensures that segmentation remains relevant and aligned with business dynamics.

## Conclusion

The K-Means model successfully identified meaningful clusters within the dataset. All evaluation metrics indicate a well-performing model with good separation and consistency.

Additionally, statistical analysis highlights Income as the most relevant variable for distinguishing between clusters.

## Technologies Used

- 'Pandas'  
- 'NumPy'  
- 'Scikit-learn'  
- 'Matplotlib'  
- 'Seaborn'  
