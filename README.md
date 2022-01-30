# Retail-Segmentation
Development of Customer segmentation for Retail Loyalty framework

**Problem Statement:**
- This project is about a superstore which caters to a vast variety of customers. Superstore’s manager has noticed that there are diminishing returns from the existing marketing strategies. Sales from the last 2 quarters have hit a plateau which has started to concern the store manager
- Store’s usual marketing campaigns includes unmonitored and untargeted approach which in the last quarter incurred some losses due to which the store manager started to look for areas of improvement. He found that the mass effectiveness of mass campaigns is very low as the cost is too high. The store already has an analytics team which has been collecting household level data from customers in the loyalty program.

**Objective of case study:**
- Identifying customers with similar behavior in the loyalty program 
- Segmenting customers with similar behavior and list down their behavioral traits 
- Basis on the profile of every cluster , we have to create campaigns which are likely to generate more revenue

**Dataset and available attributes:**
![image](https://user-images.githubusercontent.com/52121954/151711622-8a25f952-5546-487c-938d-182fb758081f.png)

**Approach:**
1. Importing the given data sets and preprocessing
2. Understanding the datasets and inferences from each datasets
3. Descriptive Statistics Analysis for the datasets (avg transaction value, basket size, frequency of visits…)
4. Exploratory analysis of customer demographic variables.
5. Feature engineering for modelling , also creating a target feature (total spend and frequency of visit/loyal customer) matrix:
6. Behavioral study of customers on basis who they are (demography) and what they do( spending, loyalty, basket size/UPT..etc).
7. Supervised learning: XGB classification Modelling - based on created target feature (labels).
8. Unsupervised learning : KMeans clustering Modelling 
9. Customer's Behavioral study for each cluster and recommended campaign type based on learnings


