### Understanding Clustering Algorithms

## Overview
This project explores clustering algorithms to segment customers based on their annual income and spending score.

## Dataset
- **File**: `Mall_Customers.csv`
- **Source**: Kaggle - Mall Customers Dataset
- **Columns**:
  - `CustomerID`: Unique ID of the customer
  - `Genre`: Gender of the customer
  - `Age`: Age of the customer
  - `Annual Income (k$)`: Income in thousand dollars
  - `Spending Score (1-100)`: A metric representing spending behavior

## Dependencies
Ensure you have the following Python libraries installed:
```sh
pip install numpy pandas matplotlib seaborn scikit-learn
```

## Steps in Analysis
1. **Data Preprocessing**:
   - Handle missing values (if any).
   - Scale numerical features using `StandardScaler`.
2. **Exploratory Data Analysis (EDA)**:
   - Statistical analysis and correlation matrix.
   - Scatter plots for feature visualization.
3. **Clustering Methods**:
   - **K-Means Clustering** (Elbow Method for optimal clusters)
   - **DBSCAN** (Density-Based Clustering)
   - **Agglomerative Clustering** (Hierarchical Clustering)
4. **Evaluation Metrics**:
   - **Silhouette Score**: Measures cluster cohesion.
   - **Calinski-Harabasz Score**: Evaluates cluster separation.
5. **Visualization**:
   - Scatter plots of clustered data.
   - PCA for dimensionality reduction.

## Usage
Run the Jupyter Notebook `01_UnderstandingClusteringAlgorithms.ipynb` step by step to execute the analysis.

## Results
- Compares different clustering approaches for customer segmentation.
- Identifies customer groups based on spending habits and income.


