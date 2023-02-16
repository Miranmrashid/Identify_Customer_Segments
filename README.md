# Identify Customer Segments


## Project Overview
The goal of this project is using unsupervised learning techniques of Principal Component Analysis (PCA) and KMeans to identify customer segments of the German population that were popular or less popular with a mail-order sales in Germany.

The data is provided by Bertelsmann partners AZ Direct and Arvato Financial Solution. There are two dataset provided first was demographic data (891,211 individuals)for the general population of Germany and the second dataset was demographic data for customers of a mail-order company (191,652 individuals). Both dataset consists of 85 different features.

### The Data
- `Udacity_AZDIAS_Subset.csv`: Demographic data for the general population of Germany; 891211 persons (rows) x 85 features (columns) **this file is removed prior to the agreement**.
- `Udacity_CUSTOMERS_Subset.csv:` Demographic data for customers of a mail-order company; 191652 persons (rows) x 85 features (columns) **this file is removed prior to the agreement**.
- `Data_Dictionary.md`: Information file about the features in the provided datasets.
- `AZDIAS_Feature_Summary.csv`: Summary of feature attributes for demographic data **this file is removed prior to the agreement**.
- `Identify_Customer_Segments.ipynb`: Jupyter Notebook divided into sections and guidelines for the project. 

### 1: Preprocessing
This step requires the assessment of missing data by using the feature summary file to map the codes provided for any missing or unknown values and converting them to NaNs, it also requires the visualization of missing data row and column wise. Then it requires to encode features based on its data types and lastly combining all the work in a single function to be reused later.

### 2: Feature Transformation
In this step data cleaning and feature scaling is conducted prior to applying dimensionality reduction. Lastly, I have interpreted the principal components.


### 3: Clustering
This step finally applies the model and trains it using Kmeans algorithm. afterwards I applied the final model to the general demographic and all the steps to the customers data. Lastly, we compare both datasets and identify the customers segments the mail order company would benefit from.

 




#### A credit to BOSCH AI TALENT ACCELERATOR (Udacity)
This project is part of the Udacity Nanodegree.
