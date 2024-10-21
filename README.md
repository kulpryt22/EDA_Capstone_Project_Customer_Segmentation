# EDA_Capstone_Project_Customer_Segmentation.ipynb

## Project Overview
This project focuses on performing **Exploratory Data Analysis (EDA)** to understand customer segmentation in a mall using a dataset of customer demographics and spending behavior. The goal is to analyze the dataset and identify key insights that can be used to categorize customers into distinct segments based on their annual income and spending habits. This type of analysis is crucial for businesses to create targeted marketing strategies and improve customer experience.

## Dataset
The dataset used for this project contains information about mall customers, including:
- **CustomerID**: Unique identifier for each customer.
- **Gender**: Gender of the customer (Male/Female).
- **Age**: Age of the customer.
- **Annual Income (k$)**: Annual income of the customer in thousands of dollars.
- **Spending Score (1-100)**: A score assigned by the mall, representing the spending habits of the customer, where 1 is the lowest and 100 is the highest.

The dataset is saved as `Mall_Customers.csv`.

## Project Goals
1. Perform exploratory data analysis to understand the distribution of customer demographics.
2. Visualize the relationships between key variables such as age, income, and spending score.
3. Use clustering techniques (e.g., K-means) to segment customers based on their income and spending behavior.
4. Provide actionable insights for targeted marketing and customer engagement strategies.

## Files in the Repository
- `Mall_Customers.csv`: The dataset used for analysis.
- `Customer_Segmentation_EDA.ipynb`: The Jupyter Notebook containing the full EDA process, visualizations, and clustering analysis.
- `README.md`: This file, providing an overview of the project, dataset, and goals.

## Libraries Used
This project was developed using the following Python libraries:
- **Pandas**: For data manipulation and analysis.
- **NumPy**: For numerical operations.
- **Matplotlib** and **Seaborn**: For data visualization.
- **Scikit-learn**: For applying the K-means clustering algorithm.

## Key Steps in the Project
1. **Data Preprocessing**: 
   - Handle missing values, if any.
   - Convert data types as required.
   - Explore basic statistics of the dataset.
   
2. **Exploratory Data Analysis**:
   - Analyze the distribution of variables like age, annual income, and spending score.
   - Identify correlations between key variables.
   - Visualize the data using histograms, box plots, and scatter plots.

3. **Customer Segmentation using K-means Clustering**:
   - Perform clustering based on annual income and spending score.
   - Visualize the clusters to identify distinct customer segments.
   
4. **Insights and Conclusions**:
   - Interpret the clusters and their significance for business strategy.
   - Discuss potential marketing approaches for each customer segment.

## Visualizations
This project includes various data visualizations to better understand the customer data:
- **Histograms**: To display the distribution of age, income, and spending score.
- **Box Plots**: To visualize outliers and the range of customer income and spending.
- **Scatter Plots**: To analyze the relationship between income and spending score.
- **Cluster Plots**: To visualize the segmentation of customers using K-means clustering.

## Usage
1. Clone the repository.
2. Install the necessary dependencies:
   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn
   ```
3. Run the Jupyter Notebook `Customer_Segmentation_EDA.ipynb` to reproduce the analysis.

## Insights
The key outcomes of this project include:
- Segmentation of customers into distinct groups such as high-income/high-spending, low-income/low-spending, etc.
- Understanding customer behavior patterns for better marketing strategies.

## Conclusion
The Customer Segmentation EDA project provides useful insights into customer demographics and purchasing behaviors. The clustering of customers helps businesses understand their target audience and customize their offerings accordingly.
