# Retail-Price-Recommendation-using-Machine-Learning
# Overview

Using historical data to determine the most profitable price for a product or service is one way to maximize company profitability. Demography, operating costs, survey data, and other factors all play a role in determining efficient pricing, as do the businesses' and goods' nature. Businesses frequently add or upgrade features to increase value to their products, which obviously has an impact on company reputation.

We must ensure that we correctly price our goods, in order to ensure that we retain our customers and make a profit. Price optimization may help businesses achieve their profit objectives, while also satisfying their customers. In this repository, we will consider the simplest price recommendation algorithm using machine learning.

In this repository we will using case from Mercari, the largest community-based shopping app in Japan. They’d like to offer pricing suggestions to sellers, but this is tough because their sellers are enabled to put just about anything, or any bundle of things, on Mercari’s marketplace.

In this machine learning project, we will build a model that automatically suggests the right product prices. We are provided of the following information:
**train_id** (the id of the listing), **name** (the title of the listing), **item_condition_id** (the condition of the items provided by the sellers), **category_name** (category of the listing), **brand_name** (the name of the brand), **price** (the price that the item was sold for. This is target variable that we will predict), **shipping** (1 if shipping fee is paid by seller and 0 by buyer), **item_description** (the full description of the item).

The data set can be downloaded from [Kaggle](https://www.kaggle.com/datasets/saitosean/mercari). To validate the result, I only need the train.tsv.

### References  

   Huge shoutout goes to Susan Li for creating the backbone of this repository:
  * [Machine Learning for Retail Price Recommendation with Python](https://towardsdatascience.com/machine-learning-for-retail-price-suggestion-with-python-64531e64186d)
