# Customer-Segmentation
This project is about how you're running a business and want to group your customers based on how they spend money. This helps in personalized marketing—like offering discounts to high-value customers or targeting low-spending customers with better deals.

This project clusters customers based on:
* Annual Income (How much they earn)
* Spending Score (How much they spend)
* Age (To analyze trends across age groups)

# How it works:

1. Prepares the Data
* Loads customer data from a CSV file.
* Picks the important features (Income, Spending, Age).
* Standardizes the data so that different scales don’t mess up the analysis.

2. Finds the Best Number of Groups
* Uses the Elbow Method (a graph that helps pick the right number of clusters).
* Decides the best number of customer segments (e.g., 4 groups).

3. Groups Customers into Clusters
* Uses K-Means clustering to assign each customer to a segment.
* Stores the cluster label in the dataset so businesses can analyze them.

4. Visualizes the Groups
* Reduces the data into 2D using PCA (Principal Component Analysis).
* Plots the clusters so we can actually see them on a graph!

5. Creates an API for Predictions
* Deploys a Flask API so businesses can send new customer data and get a predicted segment in return.
* Example: A customer enters their details → the API tells which group they belong to!

# Why is This Useful?
* Targeted Marketing: Offer exclusive deals to high-spending customers.
* Better Business Strategies: Understand customer behavior to improve services.
* Optimized Sales & Engagement: Increases engagement by 12% (as per the resume).
