---
layout: page
title: Trajectory Analysis
permalink: /forecasting/trajectories
description: Transformer Networks for Trajectory Forecasting
img: assets/img/traj_fore.png
importance: 1
category:  Trajectory Analysis
---

# Transformer Networks for Trajectory Forecasting

***Accepted at 25th International Conference on Pattern Recognition (ICPR 2020)***

Most recent successes on forecasting the people motion are based on LSTM models and all most recent progress has been achieved by modelling the social interaction among people and the people interaction with the scene. We question the use of the LSTM models and propose the novel use of Transformer Networks for trajectory forecasting. This is a fundamental switch from the sequential step-by-step processing of LSTMs to the only-attention-based memory mechanisms of Transformers. In particular, we consider both the original Transformer Network (TF) and the larger Bidirectional Transformer (BERT), state-of-the-art on all natural language processing tasks. Our proposed Transformers predict the trajectories of the individual people in the scene. These are "simple" model because each person is modelled separately without any complex human-human nor scene interaction terms. In particular, the TF model without bells and whistles yields the best score on the largest and most challenging trajectory forecasting benchmark of TrajNet. Additionally, its extension which predicts multiple plausible future trajectories performs on par with more engineered techniques on the 5 datasets of ETH + UCY. Finally, we show that Transformers may deal with missing observations, as it may be the case with real sensor data. 

Code reachable [here](https://github.com/HumaticsLAB/Trajectory-Transformer).

## Citation
If you use the code, please cite our paper. Do not hesitate to contact any of the authors with any comments or feedback.

```
@inproceedings{giuliari2021transformer,
  title={Transformer networks for trajectory forecasting},
  author={Giuliari, Francesco and Hasan, Irtiza and Cristani, Marco and Galasso, Fabio},
  booktitle={2020 25th International Conference on Pattern Recognition (ICPR)},
  pages={10335--10342},
  year={2021},
  organization={IEEE}
}
```