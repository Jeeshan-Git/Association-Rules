## Association Rule Mining: Market Basket Analysis
# Overview
This project focuses on Association Rule Mining, using the Apriori algorithm to analyze customer purchasing behavior. The objective is to identify interesting relationships between products purchased together, providing actionable insights for decision-making.

## Table of Contents
* Project Description
* Dataset Details
* Technologies Used
* Steps Performed
* Results and Insights

## Project Description
The project uses association rule mining techniques to discover relationships between items in a retail dataset. Key metrics like Support, Confidence, and Lift are utilized to evaluate the strength and significance of these relationships.

## Dataset Details
* Dataset Name: Online Retail Dataset
* Features:
* Transaction IDs
# * Product Descriptions
* Quantities
* Customer IDs
* Invoice Dates
* Preprocessing Steps:
* Handled missing values.
* Removed duplicate entries.
* Transformed data into a suitable format for association rule mining.

## Technologies Used
* Programming Language: Python
* Libraries:
* Pandas
* Numpy
* Mlxtend (for Apriori algorithm and association rule generation)

## Steps Performed
1. Data Preprocessing:
Cleaned the dataset to remove inconsistencies.
Converted data into a transactional format suitable for association rule mining.

2. Association Rule Mining:
Implemented the Apriori algorithm to generate frequent itemsets.
Extracted rules based on Support, Confidence, and Lift thresholds.

3. Analysis and Interpretation:
Analyzed generated rules to uncover significant patterns.
Provided insights into customer purchasing behaviors.

4. Insights:
Identified frequently purchased product combinations.
Highlighted strong associations between items using lift values.

## Results and Insights
* Key Rules:
* E.g., "Customers who bought [Item A] often also bought [Item B]."
* "Products X, Y, and Z are frequently purchased together."
* Metrics:
* Support: Fraction of transactions containing the itemset.
* Confidence: Likelihood of an item being purchased given another.
* Lift: Strength of the rule compared to random chance.
