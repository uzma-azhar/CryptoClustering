# CryptoClustering
This is my submission for the Module 19 challenge. In this assignment I, first:
- Normalized the data using StandardScaler()
- Found the best value for k using a for loop to compute inertia values (4)
    - random_state had to be updated to show a true curve
- Created a scatter plot to make clusters using KMeans and the normalized/scaled data

Then, I:

- Optimized the clusters with Principal Component Analysis (PCA) and reduced the features to 3 principal components
    - total explained variance was approximately 89.5% 
- Found the best value for k using a for loop to compute inertia values using the PCA data (4)
- Created a scatter plot to make clusters using KMeans and the PCA data (PC1 & PC2)

Comparing both, we can see that we find 4 clusters even with fewer features so the model performs just as well. 


