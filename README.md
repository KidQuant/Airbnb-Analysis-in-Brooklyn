# Analysis of Airbnb Listings in Brooklyn

I used machine learning to make a linear regression model using pandas, numpy, seaborn, scikit-learn to predict Airbnb listing prices in the Brooklyn area.

![Airbnb](https://kidquant.com/project/analysis-of-airbnb-listings-in-brooklyn/featured.jpg)

## Goal

Our goals involve the following:

* **Part 1:** Finding Airbnb listing trends in the Brooklyn Market
* **Part 2:** The Zillow Home Value Index (ZHVI) And Airbnb Metrics, Listing Price.
* **Part 3:** Given ZHVI and listing trends, develop model that can predict price given these two sets of features.

Using trends in the Brooklyn housing market, we can potentially forecast Airbnb listing prices in the Brooklyn area.

## Data

I used data from Airbnb listing data from [InsideAirbnb.com](http://www.insideairbnb.com), which scrapes the most recent Airbnb listing information for millions of Airbnb apartments and rooms all across the globle. I also used Home Value index and listing trends for neighborhood data from [Zillow.com](https://www.zillow.com/research/data/).

Given how large the Airbnb Listings file is, I have not included it in the repository.

## Enviroment and tools

1. Jupyter Notebook
2. Numpy
3. Pandas
4. Seaborn
5. Matplotlib
6. Scikit-learn

I chose to use the Linear Regression in my model, given the quantitiative nature of the datasets. The model achieved 55% on the training set and 45% on the testing set, with a mean-squared error of 4,976 and 3,898 on the training and testing set respectively. The model performed better once we eliminated the outliers from the dataset (53% and 61% on the training and testing set).


