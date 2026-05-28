# DFR-YOLOv12n Tomato Leaf Disease Detection Dataset

This repository provides the curated tomato leaf disease detection dataset used in the manuscript entitled “DFR-YOLOv12n: A Lightweight Detection Method for Tomato Leaf Diseases in Natural Environments via Detail-Preserving Downsampling, Feature Fusion Enhancement, and Regression Optimization”.

The dataset was constructed from multiple public sources and online image resources, followed by manual screening, relabeling, and standardization. It is designed for tomato leaf disease detection in natural environments.

## Classes

The dataset contains eight categories:

0. Bacterial_Spot  
1. Early_Blight  
2. Healthy  
3. Late_Blight  
4. Leaf_Mold  
5. Mosaic_Virus  
6. Septoria  
7. Yellow_Leaf_Curl_Virus  

## Annotation format

All annotations are provided in YOLO format.

## Dataset structure

```text
TomatoLeafDiseaseDataset/
├── train/
│   ├── images/
│   └── labels/
├── val/
│   ├── images/
│   └── labels/
├── test/
│   ├── images/
│   └── labels/
└── data.yaml
