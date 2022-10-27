# Retail-Price-Recommendation-using-Machine-Learning
# Overview

Price optimization is using historical data to identify the most appropriate price of a product or a service that maximizes the company’s profitability. There are numerous factors like demography, operating costs, survey data, etc that play a role in efficient pricing, it also depends on the nature of businesses and the product that is served. The business regularly adds/upgrades features to bring more value to the product and this obviously has a cost associated with it in terms of effort, time, and most importantly companies reputation.

As a result, it is important to understand the correct pricing, a little too high, you lose your customers and slight underpricing will result in loss of revenue. Price optimization helps businesses strike the right balance of efficient pricing, achieving profit objectives, and also serve their customers. In this repository, we will take a look at the simplistic price recommendation approach using machine learning.

Mercari, Japan’s biggest community-powered shopping app, knows one problem deeply. They’d like to offer pricing suggestions to sellers, but this is tough because their sellers are enabled to put just about anything, or any bundle of things, on Mercari’s marketplace.

In this machine learning project, we will build a model that automatically suggests the right product prices. We are provided of the following information:
**train_id** (the id of the listing), **name** (the title of the listing), **item_condition_id** (the condition of the items provided by the sellers), **category_name** (category of the listing), **brand_name** (the name of the brand), **price** (the price that the item was sold for. This is target variable that we will predict), **shipping** (1 if shipping fee is paid by seller and 0 by buyer), **item_description** (the full description of the item).

The data set can be downloaded from [Kaggle](https://www.kaggle.com/datasets/saitosean/mercari). To validate the result, I only need the train.tsv.

### References  

   Huge shoutout goes to Susan Li for creating the backbone of this repository:
  * [Machine Learning for Retail Price Recommendation with Python](https://towardsdatascience.com/machine-learning-for-retail-price-suggestion-with-python-64531e64186d)
