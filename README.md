# Greener Mercedes Benz
## Problem Statement Scenario:
Since the first automobile, the Benz Patent Motor Car in 1886, Mercedes-Benz has stood for important automotive innovations. These include the passenger safety cell with a crumple zone, the airbag, and intelligent assistance systems. Mercedes-Benz applies for nearly 2000 patents per year, making the brand the European leader among premium carmakers. Mercedes-Benz is the leader in the premium car industry. With a huge selection of features and options, customers can choose the customized Mercedes-Benz of their dreams.
To ensure the safety and reliability of every unique car configuration before they hit the road, the company’s engineers have developed a robust testing system. As one of the world’s biggest manufacturers of premium cars, safety and efficiency are paramount on Mercedes-Benz’s production lines. However, optimizing the speed of their testing system for many possible feature combinations is complex and time-consuming without a powerful algorithmic approach.
## Task:
You are required to reduce the time that cars spend on the test bench. Others will work with a dataset representing different permutations of features in a Mercedes-Benz car to predict the time it takes to pass testing. Optimal algorithms will contribute to faster testing, resulting in lower carbon dioxide emissions without reducing Mercedes-Benz’s standards.
## Dataset:
The dataset is with 8418 rows and 378 columns.
## Approach:
1.	Removed the columns with variance zero
2.	Checked for null values and duplicates
3.	Applied label encoder
4.	Performed dimensionality reduction using Principal Component Analysis
5.	Performed dimensionality reduction using correlation
6.	Performed dimensionality reduction using  recursive feature elimination
7.	Reduced the number of features to 10
8.	Built a model with XGBoost and obtained an accuracy of 80%
