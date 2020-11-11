# Building Fast Queries on a CSV
This project uses a CSV file which has data for a latops in an imaginary webstore and uses queries to show how to assess and implement the algorithms for specific use cases based on time and space concerns.  

In this project I demonstrated the following:
* How to build indexes for a CSV using dictionaries
* How to analyse the effeciency (time and space complexity) of algorithms for queryng the CSV.
* How preprocessing the can speed up the execution of the algorithm.


## resources 
[Guided Project](https://app.dataquest.io/m/481/guided-project%3A-building-fast-queries-on-a-csv/1/the-dataset)

# Data Science Outer London House Price Estimator: Project Overview
* I created a tool to estimate the house prices for properties < 40 miles from central London less than £325k (MAE ~ £19K) to help people when looking for homes at commutable distance.
* I scraped over 900 property descriptions from zoopla.co.uk using python and beautifulsoups.
* Engineered features from the text for each description to quantify how the value of house prices change if are description were to have a garden, largeness, spaciousness or an extension featured in the description.
* Optimised Linear, Lasso, and Random Forest Regressors using GridsearchCV to reach the best model.
* Built a client facing API using flask

## Code and Resources Used
**Python Version:** 3.8

**Packages:** csv, time, random.

**Data Quest Guided project:** https://www.dataquest.io/m/481-guided-project-building-fast-csv-queries/
