---
layout: page
title: Visuelle 2.0
permalink: /forecasting/visuelle
img: assets/img/vis2/sf_fore.png
description: The first, publicly available, multi-modal fashion forecasting dataset based on real-world data. 
importance: 1
category: Fashion Forecasting
---

## Dataset description
Visuelle 2.0 is a dataset containing real data for 5355 clothing products of  the retail fast-fashion Italian company, [Nuna Lie](https://www.nunalie.it/en/). Specifically, Visuelle 2.0 provides data from 6 fashion seasons (partitioned in Autumn-Winter and Spring-Summer) from 2017-2019, right before the Covid-19 pandemic. 

Each product in our dataset is accompanied by an HD image, textual tags and more. The time series data are disaggregated at the shop level, and include the sales, inventory stock, max-normalized prices (for the sake of confidentiality} and discounts. Exogenous time series data is also provided, in the form of Google Trends based on the textual tags and multivariate weather conditions of the stores' locations. Finally, we also provide purchase data for 667K customers whose identity has been anonymized, to capture personal preferences. With these data, Visuelle 2.0 allows to cope with several problems which characterize the activity of a fast fashion company: *new product demand forecasting*, *short-observation new product sales forecasting*, and *product recommendation*.

#### Different products and their data, sales, inventory and discount series
![Examples of different products and their data](/assets/img/vis2/ex2.png "Examples of different products and their data"){:class="img-responsive" height="auto" width="700px"}
![](/assets/img/vis2/ex1.png){:class="img-responsive" height="auto" width="700px"}

#### Examples of the exogenous Google Trend and weather data
![Example of the exogenous Google Trend data](/assets/img/vis2/gtrends.png "Example of the exogenous Google Trend data"){:class="img-responsive" height="auto" width="700px"}
![Extract of the exogenous weather data](/assets/img/vis2/weather.png "Extract of the exogenous weather data"){:class="img-responsive" height="auto" width="700px"}

#### Purchases for 10 different customers
![Purchases for 10 different customers](/assets/img/vis2/customer_purchases.png "Purchases for 10 different customers"){:class="img-responsive" height="auto" width="700px"}


## Data and code
You can download the Visuelle 2.0 dataset by filling out this simple form (the download link will be provided upon completion): *...*. 

The code demonstrating how to use the dataset for the forecasting tasks described in the paper and also for the RNN-based model we used to obtain the best results is available here: (Coming soon...)


