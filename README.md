# Drone Detection with YOLOv8

This project implements a real-time drone detection system using YOLOv8, trained on a custom dataset of drone images and labels.

## Features

- Real-time drone detection
- YOLOv8 model for high accuracy and speed
- Custom dataset support

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/drone-detection-yolov8.git
    cd drone-detection-yolov8
    ```

2. Install the required packages:
    ```bash
    pip install torch torchvision yolov8 opencv-python
    ```

## Usage

### Training

Train the model:
```python
from yolov8 import YOLOv8

model = YOLOv8('yolov8s.yaml')
model.train(data='data.yaml', epochs=50, batch_size=16)

```

Real-time Detection
Run the real-time detection:

```python
import cv2
from ultralytics import YOLO


model_path = 'best.pt'


```