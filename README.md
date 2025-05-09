# <p align=center>`Awesome Remote Sensing Semantic Change Detection`</p>
[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome) [![Maintenance](https://img.shields.io/badge/Maintained%3F-yes-green.svg)](https://GitHub.com/Naereen/StrapDown.js/graphs/commit-activity) [![PR's Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat)](http://makeapullrequest.com) [![made-with-Markdown](https://img.shields.io/badge/Made%20with-Markdown-1f425f.svg)](http://commonmark.org)

List of datasets, codes, and contests related to remote sensing semantic change detection 

# Papers

| Paper                                             |  Published in | Code/Project|                                  
|---------------------------------------------------|:-------------:|:------------:|
[Multitask semantic change detection guided by spatiotemporal semantic interaction](https://www.nature.com/articles/s41598-025-00750-8)|2025|-
[Enhanced SCanNet with CBAM and Dice Loss for Semantic Change Detection](https://arxiv.org/abs/2505.04199v1)|2025|-
[Semantic enhancement and change consistency network for semantic change detection in remote sensing images](https://www.tandfonline.com/doi/full/10.1080/17538947.2025.2496790)|2025|[code](https://github.com/XiaoJ058/RS-SCD)
[Recurrent Semantic Change Detection in VHR Remote Sensing Images Using Visual Foundation Models](https://ieeexplore.ieee.org/document/10929728)|2025|-
[Semantic-CD: Remote Sensing Image Semantic Change Detection towards Open-vocabulary Setting ](https://arxiv.org/abs/2501.06808v1)|2025|-
[ChangeMamba: Remote Sensing Change Detection with Spatio-Temporal State Space ](https://arxiv.org/abs/2404.03425)|2024|[code](https://github.com/ChenHongruixuan/ChangeMamba)
[Semantic change detection using a hierarchical semantic graph interaction network from high-resolution remote sensing images](https://www.sciencedirect.com/science/article/abs/pii/S0924271624001709)|2024|[code](https://github.com/long123524/HGINet-torch)
[A Decoder-Focused Multitask Network for Semantic Change Detection](https://ieeexplore.ieee.org/document/10422819)|2024|[code](https://github.com/byyztgxz/Decoder_Fusion)
Dual-Dimension Feature Interaction for Semantic Change Detection in Remote Sensing Images|2024|-
[Joint Spatio-Temporal Modeling for Semantic Change Detection in Remote Sensing Images](https://ieeexplore.ieee.org/document/10443352)|2024|[code](https://github.com/DingLei14/SCanNet)
[CGMNet: Semantic Change Detection via a Change-Aware Guided Multi-Task Network ](https://www.mdpi.com/2072-4292/16/13/2436)|2024|-
[SMNet: Symmetric Multi-Task Network for Semantic Change Detection in Remote Sensing Images Based on CNN and Transformer ](https://www.mdpi.com/2072-4292/15/4/949)|2023|-
[Bi-Temporal Semantic Reasoning for the Semantic Change Detection in HR Remote Sensing Images](https://arxiv.org/abs/2108.06103)|2022|[code](https://github.com/DingLei14/Bi-SRNet)
[SCDNET: A novel convolutional network for semantic change detection in high resolution optical remote sensing imagery](https://www.sciencedirect.com/science/article/pii/S0303243421001720)|2021|[code](https://github.com/daifeng2016/Semantic-Change-Detection)
[ChangeMask: Deep multi-task encoder-transformer-decoder architecture for semantic change detection](https://www.sciencedirect.com/science/article/abs/pii/S0924271621002835)|2021|[code](https://github.com/Z-Zheng/pytorch-change-models)
[Semantic Change Detection with Asymmetric Siamese Networks](https://arxiv.org/abs/2010.05687v2)|2020|-
[Multitask learning for large-scale semantic change detection](https://www.sciencedirect.com/science/article/abs/pii/S1077314219300992)|2019|-

# Dataset

- 2023.[**ChangeNet**](https://github.com/jankyee/ChangNet)      
The ChangeNet dataset comprises 31,000 pairs of multi-temporal images, each with a resolution of 0.3 meters.  It encapsulates a diverse array of complex scenes from 100 different cities.  Additionally, the dataset includes six pixel-level annotated categories, which encompass the classes of "building," "farmland," "bareland," "water," "road," and "unchanged". Paper: [Ji et al., 2023](https://arxiv.org/abs/2312.17428)

- 2023.[**CNAM-CD**](https://github.com/Silvestezhou/CNAM-CD)   
CNAM-CD is a multi-class change detection dataset that collects images of 12 different urban scenes from the past decade. The dataset selects 12 State-level New Areas in China as the study area and contains 2503 pairs of GeoTiff format images with a pixel size of 512×512. The images were captured at different times from 2013 to 2022. The data source is Google Earth, and the resolution is 0.5m. Paper: [Zhou et al.2023](https://www.mdpi.com/2072-4292/15/9/2464)

- 2020.[**SEmantic Change detectiON Dataset (SECOND)**](https://captain-whu.github.io/SCD/)   
SECOND, a well-annotated semantic change detection dataset, which collects 4662 pairs of aerial images from several platforms and sensors. These pairs of images are distributed over the cities such as Hangzhou, Chengdu, and Shanghai. Each image has size 512 x 512 and is annotated at the pixel level. SECOND focus on 6 main land-cover classes, i.e. , non-vegetated ground surface, tree, low vegetation, water, buildings, and playgrounds, that are frequently involved in natural and man-made geographical changes. Paper: [Yang et al.2020](https://arxiv.org/abs/2010.05687)

# Reference

- [wenhwu/awesome-remote-sensing-change-detection](https://github.com/wenhwu/awesome-remote-sensing-change-detection/)
