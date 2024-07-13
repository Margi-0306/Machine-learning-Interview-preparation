# Machine-learning-Interview-preparation

# Which functions in SQL do you like the most?
# Explain OLAP cubes and a use case explaining business analytics application.
# What are data normalization and non-normalization?
# What happens to the data of a table with foreign keys when the associated table with primary keys has been updated?
# What do you understand by cascading referential integrity?
# Explain the difference between the linear and logistic regression and use examples.
# What is an independent variable, and what if I have three independent variables in my model and no dependent variable?
# Write an equation for the multivariance or multiple regression model.
# Given a sample with n observations, how could you test a hypothesis?

To test a hypothesis given a sample with n observations, you generally follow these steps:

## State the Hypotheses:

1. **Null Hypothesis (H0)**: The hypothesis that there is no effect or difference.
2. **Alternative Hypothesis (H1)**: The hypothesis that there is an effect or difference.
   
## **Choose the Significance Level (α)**: 
Common choices for α are 0.05, 0.01, or 0.10.

## Select the Appropriate Test:

The choice of test depends on the type of data and the hypothesis. Common tests include the t-test, z-test, chi-square test, ANOVA, etc.

## Calculate the Test Statistic:
The formula for the test statistic depends on the chosen test. For example, for a one-sample t-test, the test statistic 𝑡
t is calculated as: (Mean - u)/ (s/square root(n))
Mean is the sample mean
u  is the population mean under the null hypothesis
s is the sample standard deviation
n is the sample size

## Determine the Critical Value or P-value:
For a given α, find the critical value from the statistical table corresponding to the test statistic. Alternatively, calculate the p-value, which is the probability of obtaining a test statistic at least as extreme as the one observed, given that the null hypothesis is true.

## Make a Decision:
Compare the Test Statistic to the Critical Value: If the test statistic exceeds the critical value (in magnitude for two-tailed tests), reject the null hypothesis.
Compare the P-value to α: If the p-value is less than α, reject the null hypothesis.
## Draw a Conclusion:
Based on the decision, conclude whether there is sufficient evidence to support the alternative hypothesis.

# What are the Assumptions of ANOVA.
Anova : Analysis of variance : If we want to compare more than 2 samples means so we are using anova test for that. In avova test we are using one factor is called f measure.
H0 = Null hypothesis will say mean of all sample should be same
HA = Alternative hypothesis will mean of all sample wont be same.

# What test would you use for a small sample?
For small sample test we can use t test. under t test it will depend which test we have to use means 1 tail t test and 2 tail t test.

# What is the null hypothesis? 
Hypothesis means assumatation according to business requirment we have to do some assumation and with some sample we have to perform tesimg so we are using advance statistics. 2 type of Hypothesis testing. First null : It will say that no changes in previous statment. and second aleternative hypothesis : it will say that changes in old statment 

# What are type 1 and type 2 errors?

## Type 1 Error (False Positive)
Definition: A Type 1 error occurs when the null hypothesis  is true, but we incorrectly reject it. Essentially, it's a "false positive" — detecting an effect that is not actually present.
Probability: The probability of committing a Type 1 error is denoted by the significance level 𝛼
α. Common choices for α are 0.05, 0.01, or 0.10.
Example: If a medical test incorrectly indicates that a healthy person has a disease, this is a Type 1 error.
## Type 2 Error (False Negative)
Definition: A Type 2 error occurs when the null hypothesis (H 0 ) is false, but we fail to reject it. Essentially, it's a "false negative" — failing to detect an effect that is actually present.
Probability: The probability of committing a Type 2 error is denoted by 𝛽
β. The power of a test (1 -β) is the probability of correctly rejecting a false null hypothesis.
Example: If a medical test fails to detect a disease in a person who actually has the disease, this is a Type 2 error.

# Use the following tables to write a query to retrieve data for customers who registered in the past ten days and spent over $100. Write another query to retrieve data for customers that spent over $100 in the past seven days. The first table is a customer purchase table with five columns: customer id, purchase date, product id, unit price, and units purchased. The second table is a customer details table with two columns: customer id and registration date.
# What is the probability of generating ten consecutive numbers in ascending order out of 100 numbers?
# How would you merge two tables in SQL?
# Write a function to calculate the Fibonacci code in any of these languages (VBA, Python, Java).
# What is the difference between DELETE TABLE and TRUNCATE TABLE in SQL?
# What’s the difference between an INNER and OUTER JOIN?

## Scenario based interview question

# Data Pipeline Creation: Describe how you would design and implement a data pipeline to ETL data from different sources ( SQL, API, files etc) into a data warehouse.
# Data Cleaning Strategies: How would you handle and clean a dataset that has missing values, duplicates and inconsistent data formats to prepare it for analysis?
# Handling Large Datasets: If you are working with large datasets that are causing performance issues, what strategies would you use to optimize data processing?
# Database Schema Design: Explain how you would design a normalized database schema for an e-commerce application.
# SQL Performance Tuning: What steps would you take to optimize a slow-running SQL query?
# Data Warehousing Concepts: Explain the differences between a star schema and a snowflake schema in data warehousing.
# ETL Tools: Describe your experience with ETL tools such as Apache NiFi, Talend or Microsoft SSIS. How did you use them in a project?
# Scheduling and Automation: How would you set up and manage scheduled data jobs to ensure data is loaded into the data warehouse regularly?
# Data Versioning: How would you implement data versioning in a data warehouse to keep track of changes over time?
# Data Security: Describe the steps you would take to secure sensitive data in a database and during data transmission.
#ri Big Data Technologies: Explain your experience with big data technologies such as Hadoop, Spark or Kafka. How did you use them in a project?
# Cloud Data Services: Describe how you have used cloud data warehousing services (AWS Redshift, Google BigQuery, Azure Synapse , Snowflake ) in your projects.
#s Data Integration: How would you integrate data from disparate sources ( SQL databases, APIs, third-party services etc) into a unified data warehouse?
# Data Lake vs. Data Warehouse: Explain the differences between a data lake and a data warehouse. When would you use one over the other?
# Error Handling in Data Pipelines: How do you manage and resolve errors in your data pipelines to ensure data integrity?
# Data Governance: What practices would you implement to ensure data quality, consistency, and governance in your data engineering processes?
# Scripting and Automation: Describe how you have used scripting languages (Python, Bash) to automate data processing tasks.
# Collaborative Projects: Discuss a project where you collaborated with data analysts or data scientists. How did you ensure smooth communication and integration of your work?
# Data Migration: Describe a scenario where you had to migrate data from one system to another. What challenges did you face and how did you overcome them?su
