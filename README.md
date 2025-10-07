## Object Detection

This project is a simple implementation of an object detection model built for learning purposes, using **ResNet50** as the backbone.  
The model is trained to detect **pedestrians** in images by predicting bounding boxes and class labels.

---

## Features
- Built with **PyTorch**
- Uses **ResNet50** as a feature extractor
- Trains on a pedestrian detection dataset (images + annotations)
- Visualizes:
  - Ground truth boxes (actual - green box)
  - Predicted boxes (model output - red box)
- Computes overall test accuracy

