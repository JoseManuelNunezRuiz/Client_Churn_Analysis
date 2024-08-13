# Customer Churn Analysis: Key Results and Strategic Insights

## Description
This project focuses on analyzing customer churn using machine learning techniques. The goal is to segment customers based on their churn probability and other features, and to optimize the model for predicting churn. Various techniques such as Random Forest and K-Means clustering were used to extract valuable insights and improve customer retention strategies.

## Contents
- [Exploratory Data Analysis (EDA)](#exploratory-data-analysis-eda)
- [Customer Segmentation](#customer-segmentation)
- [Model Performance](#model-performance)
- [Cluster Analysis](#cluster-analysis)
- [Conclusion and Recommendations](#conclusion-and-recommendations)
- [Contributions](#contributions)
- [License](#license)

## Exploratory Data Analysis (EDA)
The EDA involved:
- Cleaning and preprocessing the dataset
- Visualizing the distribution of churn probability and other features
- Generating descriptive statistics to understand data characteristics

## Customer Segmentation
Customer segmentation was performed using K-Means clustering with 3 clusters, as determined by the silhouette method. This segmentation helps in understanding the different customer groups based on their churn probability, monthly charges, and total charges.

## Model Performance

### Random Forest Model
- **Best Parameters:**
  - `max_depth`: None
  - `min_samples_leaf`: 2
  - `min_samples_split`: 10

- **Accuracy Score:** 0.7776
- **Classification Report:**

| Metric       | Precision | Recall | F1-Score | Support |
|--------------|-----------|--------|----------|---------|
| Class 0      | 0.83      | 0.89   | 0.86     | 471     |
| Class 1      | 0.58      | 0.47   | 0.52     | 163     |
| Accuracy     |           |        | 0.78     | 634     |
| Macro Avg    | 0.71      | 0.68   | 0.69     | 634     |
| Weighted Avg | 0.76      | 0.78   | 0.77     | 634     |

### Model Optimization
- **Accuracy Score:** 0.7603
- **Classification Report:**

| Metric       | Precision | Recall | F1-Score | Support |
|--------------|-----------|--------|----------|---------|
| Class 0      | 0.83      | 0.85   | 0.84     | 471     |
| Class 1      | 0.54      | 0.49   | 0.51     | 163     |
| Accuracy     |           |        | 0.76     | 634     |
| Macro Avg    | 0.68      | 0.67   | 0.68     | 634     |
| Weighted Avg | 0.75      | 0.76   | 0.76     | 634     |

## Cluster Analysis

| Cluster | Customer Segment                  | Average Monthly Charges | Average Total Charges | Average Churn Probability |
|---------|-----------------------------------|-------------------------|-----------------------|---------------------------|
| 0       | High-Cost, High-Risk Customers     | $73.39                  | $1158.66             | 0.91                      |
| 1       | Moderate-Cost, Low-Risk Customers  | $42.74                  | $991.12              | 0.04                      |
| 2       | Premium Customers with Low Risk    | $92.26                  | $5052.82             | 0.08                      |

### Visualizations
Visualizations include scatter plots and box plots that illustrate the distribution of churn probability and charges across different segments, providing insights into customer behavior and segment characteristics.

## Conclusion and Recommendations
The analysis provides a detailed understanding of customer segments and their churn risk. 
Recommendations include:

- **Segment 0:** Implement retention strategies such as personalized offers to reduce churn.
- **Segment 1:** Invest in loyalty programs to strengthen customer relationships and increase lifetime value.
- **Segment 2:** Explore upselling opportunities and additional services to maximize revenue.

## Contributions
Contributions are welcome. Please follow these steps to contribute:

## License
This project is licensed under the MIT License.
