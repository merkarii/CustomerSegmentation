# Customer Segmentation Using K-Means Clustering


# Overview
This project demonstrates the use of the k-Means clustering algorithm to segment customers based on their purchasing behavior. The dataset used in this project is the "Mall Customers" dataset, which includes information about customers such as age, gender, annual income, and spending score. The project aims to identify distinct customer segments to help create targeted marketing strategies.

# Prerequisites
To run the code, you will need the following libraries installed:

pandas
numpy
matplotlib
seaborn
scikit-learn
Install the libraries using pip:

bash
Copy code
pip install pandas numpy matplotlib seaborn scikit-learn

# Data

The "Mall Customers" dataset can be downloaded from Kaggle.

The dataset contains the following columns:

CustomerID: Unique identifier for the customer
Gender: Customer's gender (Male/Female)
Age: Customer's age
Annual Income (k$): Customer's annual income in thousands of dollars
Spending Score (1-100): A score assigned by the mall based on customer behavior and spending nature

# Workflow

Load and explore the dataset: Read the CSV file using pandas, check for missing values, and display summary statistics.
Visualize the data: Create a pairplot to visualize the relationships between different features.
Preprocess the data: Convert the categorical feature (Gender) to numerical values and scale the data using StandardScaler.
Determine the optimal number of clusters (k): Use the Elbow Method to find the best k value for k-Means clustering.
Apply k-Means clustering: Create a k-Means clustering model with the optimal k value and fit the model to the preprocessed dataset.
Visualize the clusters: Use PCA to reduce the dimensionality of the data for visualization and create a scatter plot of the clusters.
Analyze the clusters: Examine the characteristics of each cluster to identify distinct customer segments.

# Results 

After applying the k-Means clustering algorithm, customers were segmented into five distinct groups based on their purchasing behavior. Analyzing the characteristics of each cluster allows businesses to create targeted marketing strategies for each customer segment, improving the effectiveness of their campaigns and increasing customer satisfaction.

# License

This project is licensed under the MIT License - see the LICENSE file for details.
