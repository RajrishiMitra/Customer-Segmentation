# Customer Segmentation Project

This project aims to perform customer segmentation to group people with similar interests so that the marketing team can converge on an effective marketing plan. We compared three different clustering algorithms - KMeans, Hierarchical Clustering, and DBSCAN - to choose the appropriate algorithm that would give us the best insights. Our goals were to compare different clustering algorithms, choose the appropriate algorithm, and gain insights from the data by plotting various graphs after clustering.

## Project Structure

The project is organized as follows:

├── data/
│ ├── credit card.csv
├── src and results/
│ ├── Customer Segmentation.ipynb
├── README.md


- The `data/` directory contains the dataset used for customer segmentation (`credit card.csv`).
- The `src/` directory includes the source code files for data preprocessing, exploratory data analysis, and clustering algorithms and also the clustering results and other relevant graphs.
- `README.md` is this file, providing an overview of the project and instructions on getting started.

## Getting Started

To get started with the project, follow these steps:

1. Clone the repository:

git clone https://github.com/your-username/customer-segmentation.git


2. Place the dataset file (`credit card.csv`) inside the `data/` directory.

3. Run the main script


This will perform data preprocessing, run the three clustering algorithms, and generate the necessary visualizations.

## Exploratory Data Analysis

Before applying clustering algorithms, exploratory data analysis (EDA) was performed to gain insights into the dataset. The `Customer Segmentation.ipynb` script provides functions to explore the dataset, visualize distributions, identify correlations, and detect any outliers or missing values.

## Data Preprocessing

To ensure accurate clustering results, data preprocessing was conducted. The `Customer Segmentation.ipynb` script contains functions for handling missing values, scaling numerical features, and encoding categorical variables.

## Clustering Algorithms

We compared three clustering algorithms in this project:

1. KMeans: A partition-based clustering algorithm that assigns each data point to the nearest cluster centroid. The optimal value of K (number of clusters) was determined using techniques such as the elbow method and silhouette score.

2. Hierarchical Clustering: A bottom-up approach that builds a hierarchy of clusters. The optimal number of clusters was determined based on dendrogram analysis and other evaluation metrics.

3. DBSCAN: A density-based clustering algorithm that groups together data points in high-density regions. The optimal values of epsilon (neighborhood radius) and min_samples (minimum number of points in a neighborhood) were determined through visual inspection and evaluation metrics.

The implementation of these algorithms can be found in the `Customer Segmentation.ipynb` script.

## Results

After running the three clustering algorithms, we evaluated their performance using various metrics, including the silhouette score, inter-cluster distance, and visual inspection of cluster assignments. Based on these evaluations, we chose KMeans as the most appropriate algorithm for customer segmentation, as it provided the highest silhouette score.

The results and visualizations are displayed . The various image showcases the final clustering results obtained using KMeans.

## Conclusion

This project aimed to perform customer segmentation for effective marketing planning. By comparing three clustering algorithms - KMeans, Hierarchical Clustering, and DBSCAN - we selected KMeans as the most suitable algorithm, as it yielded the highest silhouette score. The project followed a structured approach, starting with exploratory data analysis and data preprocessing before applying the clustering algorithms.

Feel free to explore the source code and adapt it to your own datasets or business requirements. Happy clustering!



