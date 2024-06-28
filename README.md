# Advanced Cryptocurrency Market Clustering

## Project Overview
This project applies advanced data analysis techniques to cluster cryptocurrencies based on market data. It involves preprocessing, principal component analysis (PCA), and K-means clustering to discover underlying patterns in the cryptocurrency market.

## Technologies Used
- Python
- Pandas
- Scikit-learn (PCA, KMeans)
- hvPlot
- Matplotlib

## Process
1. **Data Loading and Cleaning:** Load market data and perform initial exploration.
2. **Data Normalization:** Utilize Scikit-learn's `StandardScaler` to normalize market data.
3. **Principal Component Analysis (PCA):** Reduce dimensionality to three principal components, preserving 88.44% of the variance.
4. **Cluster Analysis:** Use the Elbow Method to determine the optimal number of clusters (k=4) and apply K-Means clustering both on original and PCA-reduced data.
5. **Visualization:** Visualize the clustering results to interpret and analyze the market behaviors.

## Results
- The PCA transformation and clustering reveal that four clusters best summarize the cryptocurrency market behaviors.
- Consistent results between the original and PCA-reduced data validate the robustness of the analysis.

## Conclusion
This project demonstrates the effective use of machine learning and data visualization to analyze and interpret complex datasets in the cryptocurrency market, providing actionable insights for market segmentation.

