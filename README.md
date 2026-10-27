# K-Means Customer Segmentation

## Project Overview
This project implements the K-Means clustering algorithm on the Mall Customers dataset to identify customer groups based on annual income and spending score.

## Objectives
- Implement K-Means clustering using Python.
- Determine the number of clusters using the Elbow Method.
- Evaluate clustering quality using the Silhouette Score and Davies-Bouldin Index.
- Visualize customer clusters and centroids.
- Predict clusters for new customers.

## Dataset
The Mall Customers dataset contains 200 customer records and 5 columns.

Features used:
- Annual Income (k$)
- Spending Score (1-100)

## Technologies Used
- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

## Algorithm
K-Means Clustering

## Results
- Number of clusters: 5
- Silhouette Score: 0.5547
- Davies-Bouldin Index: 0.5722
- Total customers clustered: 200

## Files
- `mdm_kmeans.ipynb` — Python implementation and analysis.
- `Mall_Customers.csv` — Dataset used for clustering.

## How to Run
1. Download the notebook and dataset.
2. Open the notebook in Google Colab.
3. Upload `Mall_Customers.csv` when prompted.
4. Run the notebook cells in sequence.

## Conclusion
K-Means successfully grouped customers based on annual income and spending score. The resulting clusters were evaluated using clustering metrics and visualizations, and the model was used to predict clusters for new customers.
