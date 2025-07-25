# <p align=center>`Awesome Remote Sensing Semantic Change Detection`</p>
[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome) [![Maintenance](https://img.shields.io/badge/Maintained%3F-yes-green.svg)](https://GitHub.com/Naereen/StrapDown.js/graphs/commit-activity) [![PR's Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat)](http://makeapullrequest.com) [![made-with-Markdown](https://img.shields.io/badge/Made%20with-Markdown-1f425f.svg)](http://commonmark.org)

List of datasets, codes, and contests related to remote sensing semantic change detection 


# Papers

| Paper                                          | Published in | Code/Project| Model name|                          
|------------------------------------------------|:------------:|:-----------:|:---------:|
[AtrousMamaba: An Atrous-Window Scanning Visual State Space Model for Remote Sensing Change Detection](https://arxiv.org/abs/2507.16172)|2025|-|AWMambaSCD|
[Graph Aggregation Prototype Learning for Semantic Change Detection in Remote Sensing](https://arxiv.org/abs/2507.10938)|2025|-|GAPL-SCD|
[MSSDF: Modality-Shared Self-supervised Distillation for High-Resolution Multi-modal Remote Sensing Image Learning](https://arxiv.org/abs/2506.09327)|2025|[code](https://github.com/CVEO/MSSDF)|MSSDF|
[A Semantic Change Detection Network Based on Boundary Detection and Task Interaction for High-Resolution Remote Sensing Images](https://ieeexplore.ieee.org/document/11015343)|2025|[code](https://github.com/TangYJ1229/BT-SCD)|BT-SCD|
[Multitask semantic change detection guided by spatiotemporal semantic interaction](https://www.nature.com/articles/s41598-025-00750-8)|2025|-|STGNet|
[Enhanced SCanNet with CBAM and Dice Loss for Semantic Change Detection](https://arxiv.org/abs/2505.04199v1)|2025|[code](https://github.com/Buddhi19/SCanNet)|SCanNet + CBAM + L<sub>Dice</sub> |
[Semantic enhancement and change consistency network for semantic change detection in remote sensing images](https://www.tandfonline.com/doi/full/10.1080/17538947.2025.2496790)|2025|[code](https://github.com/XiaoJ058/RS-SCD)|SCNet|
[Recurrent Semantic Change Detection in VHR Remote Sensing Images Using Visual Foundation Models](https://ieeexplore.ieee.org/document/10929728)|2025|[code](https://github.com/Gaia0811/VFM-SCD)|VFM-ReSCD|
[Semantic-CD: Remote Sensing Image Semantic Change Detection towards Open-vocabulary Setting ](https://arxiv.org/abs/2501.06808v1)|2025|-|Semantic-CD|
[ChangeMamba: Remote Sensing Change Detection with Spatio-Temporal State Space ](https://arxiv.org/abs/2404.03425)|2024|[code](https://github.com/ChenHongruixuan/ChangeMamba)|MamabaSCD|
[SCD-SAM: Adapting Segment Anything Model for Semantic Change Detection in Remote Sensing Imagery](https://ieeexplore.ieee.org/document/10543161)|2024|[code](https://github.com/yzygit1230/SCD-SAM)|SCD-SAM|
[A Late-Stage Bitemporal Feature Fusion Network for Semantic Change Detection](https://arxiv.org/pdf/2406.10678)|2024|[code](https://github.com/STORMTROOPERRR/RSISCD)|LSAFNet|
[Semantic change detection using a hierarchical semantic graph interaction network from high-resolution remote sensing images](https://www.sciencedirect.com/science/article/abs/pii/S0924271624001709)|2024|[code](https://github.com/long123524/HGINet-torch)|HGINet|
[A Decoder-Focused Multitask Network for Semantic Change Detection](https://ieeexplore.ieee.org/document/10422819)|2024|[code](https://github.com/byyztgxz/Decoder_Fusion)|DEFO-MLTSCD|
Dual-Dimension Feature Interaction for Semantic Change Detection in Remote Sensing Images|2024|-|DFINet|
[Joint Spatio-Temporal Modeling for Semantic Change Detection in Remote Sensing Images](https://ieeexplore.ieee.org/document/10443352)|2024|[code](https://github.com/DingLei14/SCanNet)|SCanNet|
[CGMNet: Semantic Change Detection via a Change-Aware Guided Multi-Task Network ](https://www.mdpi.com/2072-4292/16/13/2436)|2024|-|CGMNet|
[SMNet: Symmetric Multi-Task Network for Semantic Change Detection in Remote Sensing Images Based on CNN and Transformer ](https://www.mdpi.com/2072-4292/15/4/949)|2023|-|SMNet|
[Bi-Temporal Semantic Reasoning for the Semantic Change Detection in HR Remote Sensing Images](https://arxiv.org/abs/2108.06103)|2022|[code](https://github.com/DingLei14/Bi-SRNet)|Bi-SRNet|
[SCDNET: A novel convolutional network for semantic change detection in high resolution optical remote sensing imagery](https://www.sciencedirect.com/science/article/pii/S0303243421001720)|2021|[code](https://github.com/daifeng2016/Semantic-Change-Detection)|SCDNET|
[ChangeMask: Deep multi-task encoder-transformer-decoder architecture for semantic change detection](https://www.sciencedirect.com/science/article/abs/pii/S0924271621002835)|2021|[code](https://github.com/Z-Zheng/pytorch-change-models)|ChangeMask|
[Semantic Change Detection with Asymmetric Siamese Networks](https://arxiv.org/abs/2010.05687v2)|2020|-|ASN-ATL|
[Multitask learning for large-scale semantic change detection](https://www.sciencedirect.com/science/article/abs/pii/S1077314219300992)|2019|-||

# Benchmark

## SECOND Dataset

|               Model               |  mIoU |  SeK  | Score |
| :-------------------------------: | :---: | :---: | :---: |
|             AWMambaSCD            | 73.66 | 24.95 | 39.56 |
|               BT-SCD              | 73.67 | 24.21 | 39.04 |
|               STGNet              | 72.83 | 22.45 | 37.56 |
| SCanNet + CBAM + L<sub>Dice</sub> | 73.63 | 24.25 | 39.06 |
|               SCNet               | 73.85 | 23.99 | 38.95 |
|             VFM-ReSCD             | 73.33 | 24.01 | 38.81 |
|            Semantic-CD            | 75.10 | 23.85 | 39.23 |
|             MamabaSCD             | 73.68 | 22.92 | 38.15 |
|              SCD-SAM              | 77.75 | 32.44 | 46.03 |
|              LSAFNet              | 74.01 | 24.32 | 39.23 |
|               HGINet              |   --  |   --  |   --  |
|            DEFO-MLTSCD            | 73.76 | 23.73 | 38.74 |
|               DFINet              | 72.61 | 20.12 | 35.87 |
|              SCanNet              | 73.42 | 23.94 | 38.78 |


# Datasets

- 2023.[**ChangeNet**](https://github.com/jankyee/ChangNet)      
The ChangeNet dataset comprises 31,000 pairs of multi-temporal images, each with a resolution of 0.3 meters.  It encapsulates a diverse array of complex scenes from 100 different cities.  Additionally, the dataset includes six pixel-level annotated categories, which encompass the classes of "building," "farmland," "bareland," "water," "road," and "unchanged". Paper: [Ji et al., 2023](https://arxiv.org/abs/2312.17428)

- 2023.[**CNAM-CD**](https://github.com/Silvestezhou/CNAM-CD)   
CNAM-CD is a multi-class change detection dataset that collects images of 12 different urban scenes from the past decade. The dataset selects 12 State-level New Areas in China as the study area and contains 2503 pairs of GeoTiff format images with a pixel size of 512×512. The images were captured at different times from 2013 to 2022. The data source is Google Earth, and the resolution is 0.5m. Paper: [Zhou et al.2023](https://www.mdpi.com/2072-4292/15/9/2464)

- 2022.[**Landsat SCD**](https://figshare.com/articles/figure/Landsat-SCD_dataset_zip/19946135/1)   
The Landsat SCD dataset consists of 8468 pairs of images, each with a fixed size of 416×416 pixels and a resolution of 30 m. The dataset involves one no-change class and four land cover classes, including cropland, desert, building, and water. Paper: [Yuan et al.2022](https://www.tandfonline.com/doi/full/10.1080/17538947.2022.2111470)

- 2020.[**Hi-UCD**](https://github.com/Daisy-7/Hi-UCD-S)   
Hi-UCD focuses on urban changes and uses ultra-high resolution images to construct multi-temporal semantic changes to achieve refined change detection. The study area of Hi-UCD is a part of Tallinn, the capital of Estonia, with an area of 30km2. There are 359 image pairs in 2017-2018, 386 pairs in 2018-2019, and 548 pairs in 2017-2019, including images, semantic maps, and change maps at different times. Each image has a size of 1024 x 1024 and a spatial resolution of 0.1 m. There are 9 types of objects, including natural objects (water, grassland, woodland, bare land), artificial objects (Building,greenhouse, road, bridge), and others (change-related), basically include all types of urbanland cover in Estonia. Paper: [Tian et al.2020](https://arxiv.org/abs/2011.03247)

- 2020.[**SEmantic Change detectiON Dataset (SECOND)**](https://captain-whu.github.io/SCD/)   
SECOND, a well-annotated semantic change detection dataset, which collects 4662 pairs of aerial images from several platforms and sensors. These pairs of images are distributed over the cities such as Hangzhou, Chengdu, and Shanghai. Each image has size 512 x 512 and is annotated at the pixel level. SECOND focus on 6 main land-cover classes, i.e. , non-vegetated ground surface, tree, low vegetation, water, buildings, and playgrounds, that are frequently involved in natural and man-made geographical changes. Paper: [Yang et al.2020](https://arxiv.org/abs/2010.05687)

- 2019.[**High Resolution Semantic Change Detection (HRSCD) Dataset**](https://ieee-dataport.org/open-access/hrscd-high-resolution-semantic-change-detection-dataset)   
This dataset contains 291 coregistered image pairs of RGB aerial images from IGS's BD ORTHO database. Pixel-level change and land cover annotations are provided, generated by rasterizing Urban Atlas 2006, Urban Atlas 2012, and Urban Atlas Change 2006-2012 maps. Paper: [Daudt et al.2019](https://www.sciencedirect.com/science/article/pii/S1077314219300992)


# Tools and libraries

- [Open-CD](https://github.com/likyoo/open-cd): An open source change detection toolbox based on a series of open source general vision task tools.
- [torchange](https://github.com/Z-Zheng/pytorch-change-models): A Unified Change Representation Learning Benchmark Library.

  
# Reference

- [wenhwu/awesome-remote-sensing-change-detection](https://github.com/wenhwu/awesome-remote-sensing-change-detection/)
