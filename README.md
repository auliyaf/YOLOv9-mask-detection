# YOLO v9 Overview
YOLOv9 is a powerful computer vision model for object detection, developed by Chien-Yao Wang, I-Hau Yeh, and Hong-Yuan Mark Liao. It introduces the YOLOv9 and GELAN architectures, accessible through the accompanying Python repository. While YOLOv9 excels at object detection, it currently does not support segmentation, classification, or other related tasks ( 10 Mar 2024).

This solution fundamentally relies on two groundbreaking innovations: Programmable Gradient Information (PGI) and the lightweight Generalized Efficient Layer Aggregation Network (GELAN) architecture.

Programmable Gradient Information (PGI) combats information loss in deep neural networks. PGI ensures complete input data is used in objective function calculations, enabling accurate gradient generation for network weight updates.

The Generalized Efficient Layer Aggregation Network (GELAN) leverages gradient path planning to improve parameter utilization. This lightweight architecture, particularly when integrated with PGI, yields superior object detection performance on the MS COCO dataset compared to existing state-of-the-art approaches.

Exceptional Performance: The utilization of GELAN and PGI in object detection tasks based on the MS COCO dataset has demonstrated superior results compared to alternative approaches. Notably, it excels in parameter optimization and accuracy, surpassing even models pre-trained on extensive datasets

**DataSet**
- [DataSet](https://www.kaggle.com/datasets/andrewmvd/face-mask-detection)

**Model Result Folder**
- [Model Result](https://www.kaggle.com/code/auliyaaaf/yolov9-face-mask-detection)

**Repository**
* [Repository](https://github.com/WongKinYiu/yolov9/tree/main)

**Paper**
* [Paper](https://arxiv.org/abs/2402.13616)