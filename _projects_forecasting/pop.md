---
layout: page
title: POP-Mining-POtential-Performance
permalink: /forecasting/pop
img: assets/img/pop_thumbnail.png
description: The first data-centric pipeline to generate exogenousobservation data for the New Fashion Product Performance Forecasting problem. 
importance: 1
category: Fashion Forecasting
---
***Accepted at the European Conference on Computer Vision @ ECCV2022 @ Tel-Aviv***

## POP description

We create a data-centric pipeline that is able to extract a highly predictive signal from the web, dubbed “POtential Performance” (POP), which can be fed into any
NFFPF forecasting model as an additional variable and lead to more accurate forecasts. The pipeline is based on a cross-modal query expansion. The input is a single probe image of the product to be analyzed, or a photorealistic rendering. The pipeline first extracts textual tags from the probe
or directly considers the associated technical sheet. The tag set is expanded with positive and negative tags that are used to perform a time-dependent query on the web, i.e., collecting images of “fashionable” and “unfashionable” items related to the tags, which have been uploaded during some specified Kpast intervals
in the past. All these images are used to confidently learn a binary classifier that captures what is fashionable VS unfashionable in that interval. This learning procedure prunes noisy images from both the “fashionable” and “unfashionable” classes, resulting in a robust model. Subsequently, pruned positive
images are projected into an embedding space by the learned model andcompared with the (also projected) initial probe image, providing the Kpast-long POP signal. The POP signal indicates how popular the probe could have been
if it were available earlier in the past, and how this notion evolved over time. After its formation, POP can be used as an additional, exogenous variable in any forecasting model along with the probe item.

![POP data-centric pipeline](/assets/img/pop/pop_pipeline.png "Data-centric pipeline to create POP"){:class="img-responsive" height="auto" width="750px"}


## Data and code
You can download the POP signals and the GTM architecture to use them [here](https://github.com/HumaticsLAB/POP-Mining-POtential-Performance)

## Citation
If you use POP signal, please cite our paper. Do not hesitate to contact any of the authors with any comments or feedback.

```
COMING SOON
```


