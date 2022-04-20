---
layout: page
title: "MX-LSTM: Mixing Tracklets and Vislets to Jointly Forecast Trajectories and Head Poses"
permalink: /forecasting/trajectories
description: Trajectory Forecasting
img: assets/img/mx-lstm.png
importance: 2
category:  Trajectory Analysis
---

***IEEE Conference on Computer Vision and Pattern Recognition (CVPR), 2018***

Recent approaches on trajectory forecasting use tracklets to predict the future positions of pedestrians exploiting Long Short Term Memory (LSTM) architectures. This paper shows that adding vislets, that is, short sequences of head pose estimations, allows to increase significantly the trajectory forecasting performance. We then propose to use vislets in a novel framework called MX-LSTM, capturing the interplay between tracklets and vislets thanks to a joint unconstrained optimization of full covariance matrices during the LSTM backpropagation. At the same time, MX-LSTM predicts the future head poses, increasing the standard capabilities of the long-term trajectory forecasting approaches. With standard head pose estimators and an attentional-based social pooling, Mixing-LSTM scores the new trajectory forecasting state-of-the-art in all the considered datasets (Zara01, Zara02, UCY, and TownCentre) with a dramatic margin when the pedestrians slow down, a case where most of the forecasting approaches struggle to provide an accurate solution.


## Citation
If you use the code, please cite our paper. Do not hesitate to contact any of the authors with any comments or feedback.

```
@InProceedings{Hasan_2018_CVPR,
author = {Hasan, Irtiza and Setti, Francesco and Tsesmelis, Theodore and Del Bue, Alessio and Galasso, Fabio and Cristani, Marco},
title = {MX-LSTM: Mixing Tracklets and Vislets to Jointly Forecast Trajectories and Head Poses},
booktitle = {Proceedings of the IEEE Conference on Computer Vision and Pattern Recognition (CVPR)},
month = {June},
year = {2018}
}
```