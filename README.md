# Traffic Vehicle Detection using YOLOv8

Developed a deep learning-based vehicle detection system using YOLOv8 for traffic surveillance applications.  

The project involved baseline evaluation, transfer learning, and multiple optimization techniques including learning rate tuning, data augmentation, batch size adjustment, and regularization.  

Results demonstrate significant improvements in model generalization and detection performance, highlighting the importance of systematic evaluation and domain-specific fine-tuning.


## Project Overview

The goal of this project is to detect and classify vehicles in traffic scenes, including:

- Car
- Van
- Truck
- Bus

## Dataset

The dataset was sourced from Roboflow:

https://universe.roboflow.com/trafficimages-rijok/traffic-dataset-zisvr

It contains:

- 2009 training images  
- 332 validation images  
- 195 test images  

### Class Distribution

| Class | Instances |
|------|----------|
| Car  | 6319     |
| Van  | 2066     |
| Truck| 789      |
| Bus  | 369      |


## Model

- YOLOv8 (Ultralytics)
- Pretrained on COCO dataset
- Fine-tuned on traffic dataset


## Methodology

The project includes:

- Baseline model analysis
- Transfer learning (frozen & full fine-tuning)
- Learning rate optimization (Step vs Cosine)
- Data augmentation strategies
- Batch size tuning
- Regularization (Dropout & Label Smoothing)


## Results

Final model performance on test set:

- Precision: 0.858  
- Recall: 0.719  
- mAP@50: 0.821  
- mAP@50–95: 0.670  


## Files

- `notebook/Final_DL_Project.ipynb` → Model implementation  
- `docs/DL_Project_Report.pdf` → Full report  


## Purpose

This project demonstrates my ability to:

- Apply deep learning for object detection  
- Fine-tune pretrained models  
- Analyze and improve model performance  
- Work with real-world datasets  
