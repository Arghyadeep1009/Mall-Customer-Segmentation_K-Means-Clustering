# Customer Segmentation using K-Means Clustering

This project uses the K-Means clustering algorithm to segment customers based on their annual income and spending score. The goal is to identify distinct groups of customers for targeted marketing strategies.

## Project Overview

Customer segmentation is a crucial aspect of any business strategy, helping to understand the distinct groups within a customer base. By applying K-Means clustering, we can identify groups of customers with similar behaviors and preferences.

## Dataset

The dataset used in this project is the Mall Customers dataset, which contains the following columns:
- `CustomerID`: Unique ID for each customer
- `Gender`: Gender of the customer
- `Age`: Age of the customer
- `Annual Income (k$)`: Annual income of the customer in thousands of dollars
- `Spending Score (1-100)`: Spending score assigned by the mall based on customer behavior and spending nature

## Project Structure

1. **Data Collection and Analysis**
   - Loading the data from a CSV file
   - Performing basic exploratory data analysis (EDA)
   - Checking for missing values

2. **Feature Selection**
   - Selecting `Annual Income` and `Spending Score` as features for clustering

3. **Choosing the Number of Clusters**
   - Using the Elbow Method to determine the optimal number of clusters
   - Plotting the Within-Cluster Sum of Squares (WCSS) for different numbers of clusters

4. **Training the K-Means Clustering Model**
   - Training the K-Means model with the optimal number of clusters

5. **Visualizing the Clusters**
   - Plotting the clusters and their centroids

6. **Predicting Customer Clusters**
   - Function to predict the cluster of a new customer based on annual income and spending score

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/customer-segmentation.git
   ```

2. Navigate to the project directory:
   ```bash
   cd customer-segmentation
   ```

3. Install the required packages:
   ```bash
   pip install -r requirements.txt
   ```

## Usage

1. Run the script:
   ```bash
   python customer_segmentation.py
   ```

2. Enter the annual income and spending score of a customer when prompted:
   ```bash
   Enter annual income of customer: 70
   Enter spending score of customer: 40
   ```

3. The script will output the cluster to which the customer belongs:
   ```bash
   The customer with annual income 70 and spending score 40 belongs to cluster 3
   ```

## Results

- **Elbow Method Plot**: Used to determine the optimal number of clusters
- **Cluster Visualization**: Scatter plot showing different clusters and their centroids
- **Cluster Prediction**: Function to predict the cluster of a new customer based on annual income and spending score

## Acknowledgements

- The dataset is sourced from the UCI Machine Learning Repository.
- The project is inspired by various online tutorials and resources on customer segmentation and K-Means clustering.

