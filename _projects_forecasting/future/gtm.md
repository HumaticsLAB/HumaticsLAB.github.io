---
layout: page
title: GTM-Transformer
permalink: /forecasting/gtm
img: assets/img/gtm.png
description: Multimodal Forecasting of New Fashion Product Sales with Image-based Google Trends.
importance: 2
category: Fashion Forecasting
---

This work investigates the effectiveness of systematically probing Google Trends against textual translations of visual aspects as exogenous knowledge to predict the sales of brand-new fashion items, where past sales data is not available, but only an image and few metadata are available. In particular, we propose GTM-Transformer, standing for Google Trends Multimodal Transformer, whose encoder works on the representation of the exogenous time series, while the decoder forecasts the sales using the Google Trends encoding, and the available visual and metadata information. Our model works in a non-autoregressive manner, avoiding the compounding effect of the first-step errors. As a second contribution, we present the first version of VISUELLE dataset, which is the first publicly available dataset for the task of new fashion product sales forecasting, containing the sales of 5577 new products sold between 2016-2019, derived from genuine historical data of Nunalie, an Italian fast-fashion company. Our dataset is equipped with images of products, metadata, related sales, and associated Google Trends. We use VISUELLE to compare our approach against state-of-the-art alternatives and numerous baselines, showing that GTM-Transformer is the most accurate in terms of both percentage and absolute error. It is worth noting that the addition of exogenous knowledge boosts the forecasting accuracy by 1.5% WAPE wise, showing the importance of exploiting Google Trends.

Dataset and Code reachable [here](https://github.com/HumaticsLAB/GTM-Transformer).

## Citation
If you use GTM-Transformer or the first version of the dataset VISUELLE, please cite our paper. Do not hesitate to contact any of the authors with any comments or feedback.

```
@misc{https://doi.org/10.48550/arxiv.2109.09824,
  doi = {10.48550/ARXIV.2109.09824},
  url = {https://arxiv.org/abs/2109.09824},
  author = {Skenderi, Geri and Joppi, Christian and Denitto, Matteo and Cristani, Marco},
  keywords = {Computer Vision and Pattern Recognition (cs.CV), Machine Learning (cs.LG), FOS: Computer and information sciences, FOS: Computer and information sciences},
  title = {Well Googled is Half Done: Multimodal Forecasting of New Fashion Product Sales with Image-based Google Trends},
  publisher = {arXiv},
  year = {2021},
  copyright = {arXiv.org perpetual, non-exclusive license}
}
```
