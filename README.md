# Project Motivation

The aim of this project is to perform an analysis on a Boston Airbnb dataset to explore the relationships between various aspects of a listing and its price, availability, and superhost status. The project seeks to answer the following three main questions:

1. What are the aspects of a listing that best correlate to price?
2. What are the aspects of a listing that best correlate to availability (lack of bookings)?
3. What are the features that best correlate to a superhost?

# Libraries Used
The following libraries have been used in this project:

* pandas
* numpy
* seaborn
* BeautifulSoup
* urllib
* selenium
* sklearn
* matplotlib
* requests
* validators

# Files in Repository
The repository includes the following files:

* README.md: This file provides an overview of the project, the libraries used, files in the repository, summary of results, and acknowledgments.
* Boston_Airbnb.ipynb: This Jupyter notebook contains the main code for the analysis.

# Summary of Results
After performing the analysis, we have found that the three main variables that best correlate to price are:

1- Number of people the listing accommodates
2- Number of beds
3- Number of bedrooms
On the other hand, the three main variables that best correlate to availability_365 (lack of bookings) are:

1- host_is_superhost (negatively correlated)
2- maximum_nights
3- reviews_per_month (negatively correlated)
Finally, the three main variables that best correlate to host_is_superhost are:

1- number_of_reviews_ltm (last twelve months)
2- number_of_reviews_l30d (last 30 days)
3- number_of_reviews
# Acknowledgments
I would like to thank Airbnb for providing the dataset used for this analysis. Additionally, I would like to thank the various libraries used in this project, without which this analysis would not have been possible.
