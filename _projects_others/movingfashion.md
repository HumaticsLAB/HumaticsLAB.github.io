---
layout: page
title: MovingFashion
permalink: /retrieval/movingfashion
img: assets/img/movingfashion.png
description: The first, publicly available dataset for the video2shop retrieval challenge.
importance: 1
category: Image Retrieval
---

***Accepted at IEEE/CVF Winter Conference on Applications of Computer Vision 2022***

Retrieving clothes which are worn in social media videos (Instagram, TikTok) is the latest frontier of e-fashion, referred to as "video-to-shop" in the computer vision literature. In this paper we present MovingFashion, the first publicly available dataset to cope with this challenge. MovingFashion is composed of 14855 social videos, each one of them associated to e-commerce "shop" images where the corresponding clothing items are clearly portrayed. In addition, we present a network for retrieving the shop images in this scenario, dubbed SEAM Match-RCNN. The model is trained by image-to-video domain adaptation, allowing to use video sequences where only their association with a shop image is given, eliminating the need of millions of annotated bounding boxes. SEAM Match-RCNN builds an embedding, where an attention-based weighted sum of few frames (10) of a social video is enough to individuate the correct product within the first 5 retrieved items in a 14K+ shop element gallery with an accuracy of 80%. This provides the best performance on MovingFashion, comparing exhaustively against the related state-of-the-art approaches and alternative baselines.


Dataset and Code reachable [here](https://github.com/HumaticsLAB/SEAM-Match-RCNN).

## Citation
If you use MovingFashion or SEAM Match-RCNN, please cite our paper. Do not hesitate to contact any of the authors with any comments or feedback.

```
@inproceedings{godi2022movingfashion,
  title={MovingFashion: a Benchmark for the Video-to-Shop Challenge},
  author={Godi, Marco and Joppi, Christian and Skenderi, Geri and Cristani, Marco},
  booktitle={Proceedings of the IEEE/CVF Winter Conference on Applications of Computer Vision},
  pages={1678--1686},
  year={2022}
}
```