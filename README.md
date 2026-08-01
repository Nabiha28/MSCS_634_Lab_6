# MSCS 634 Lab 6 - Association Rule Mining

## Purpose

The purpose of this lab is to explore association rule mining using the Apriori and FP-Growth algorithms on the Online Retail dataset. The lab demonstrates how frequent itemsets and association rules can be discovered and visualized using Python.

## Dataset

- Online Retail Dataset (UCI Machine Learning Repository)

## Methods Used

- Data cleaning and preprocessing
- Exploratory data analysis
- Frequent itemset mining using Apriori
- Frequent itemset mining using FP-Growth
- Association rule generation
- Data visualization using Seaborn

## Key Insights

- Frequently purchased products were identified using Apriori and FP-Growth.
- Association rules revealed products that are commonly purchased together.
- FP-Growth executed faster than Apriori due to its FP-tree structure.

## Challenges

- Removed missing values.
- Removed cancelled transactions.
- Chose suitable support and confidence thresholds for meaningful rules.

## Tools Used

- Python
- Pandas
- Seaborn
- Matplotlib
- MLxtend
- Google Colab
