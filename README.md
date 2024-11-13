# GB Road Condition Detection Using YOLOv5

## Project Overview
This project aims to develop an object detection model for identifying road conditions and directions (left turn, right turn, and straight) on the challenging roads of Gilgit. Leveraging the YOLOv5 architecture, this model detects these road features and unexpected obstacles in real-time, enhancing safety for autonomous navigation and driver assistance systems.
## Introduction
The project involves detecting various road conditions in Gilgit by developing an object detection model. YOLOv5 is chosen for its balance of speed and accuracy, suitable for real-time applications. This model can support autonomous driving, driver assistance systems, and road condition monitoring.

## Objective
The objective is to build a reliable and efficient object detection model that can:

Process and preprocess road condition images.
Implement YOLOv5 for detecting specific road conditions.
Train and fine-tune the model on labeled datasets.
Evaluate and visualize the model's performance.
## Dataset
The dataset, sourced from Roboflow, includes labeled images categorized as:

Straight
Left Turn
Right Turn
Unexpected Obstacles
Data Division:

Training Set: 70%
Validation Set: 15%
Test Set: 15%
## Image Preprocessing: 
Images were resized and normalized to optimize YOLOv5 input.
## Model Architecture
YOLOv5 was selected for its effectiveness in real-time object detection. The architecture includes:

Backbone: CSPDarknet53 for feature extraction.
Neck: PANet layers for feature fusion.
Head: Outputs bounding boxes and class probabilities.
Hyperparameters:

Input Size: 416x416 pixels
Batch Size: 16
Epochs: 50
## Learning Rate: 
Experimented with values from 0.001 to 0.01
## Results
The model was trained for 25 epochs, achieving the following performance metrics:

Validation Accuracy: ~85%
Training Loss: Converged after 25 epochs
## Conclusion
This project successfully implemented YOLOv5 for detecting road conditions and turns on Gilgit roads. Key achievements include:

## Model Accuracy:
Achieved around 85% on the validation set, indicating reliable performance.
Data Augmentation: Techniques like rotation and scaling improved model generalization.
Visualization: Detection visualizations demonstrated the model's efficacy.

