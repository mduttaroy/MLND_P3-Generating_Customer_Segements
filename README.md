# MLND_P3: Generating Customer Segements

An unsupervised machine learning project to generate customer segments for a wholesale distributor, hidden in the clientele data.
This is the 4th project in Udacity Machine Learning Nano-Degree program.

## Project Description
#### Background:
An imaginery wholesale distributor in Lisbon, Portugal recently tested a change to their delivery method for some customers, by moving from a morning delivery service five days a week to a cheaper evening delivery service three days a week. Initial testing did not discover any significant unsatisfactory results, so they implemented the cheaper option for all customers. Almost immediately, the distributor began getting complaints about the delivery service change and customers were canceling deliveries — losing the distributor more money than what was being saved.
### Goal:
The wholesale distributor has collected a vast amount data on product spending for customers and intend to identify customer segments hidden in the data.They want to find what types of customers they have which will help them make better, more informed business decisions in the future.

With this goal, we will first explore the data by selecting a small subset to sample and determine if any product categories highly correlate with one another. Afterwards, we will preprocess the data by scaling each product category and then identifying (and removing) unwanted outliers. With the good, clean customer spending data, we will apply PCA transformations to the data and implement clustering algorithms to segment the transformed customer data. 

Many companies today collect vast amounts of data on customers and clientele, and have a strong desire to understand the meaningful relationships hidden in their customer base. Being equipped with this information can assist a company engineer future products and services that best satisfy the demands or needs of their customers.

## Softwares & Libraries
This project uses the following software and Python libraries:
* Python 2.7
* NumPy
* Pandas
* Matplotlib
* Scikit-learn (V0.17)
* Jupyter Notebook