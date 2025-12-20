# Pedestrian Traffic Light Detection

## Overview
This repository implements a pedestrian traffic light detection system using deep learning. The project was initially conceived to support visually impaired pedestrians by enabling systems that can recognize pedestrian traffic light states and communicate this information through assistive technologies.

The current implementation focuses on object detection using the YOLOv8 model, supporting inference on images and video streams for research and development purposes in intelligent transportation systems.

---

## Motivation
This project was originally initiated with an accessibility-focused objective. For visually impaired individuals, safely navigating pedestrian crossings remains a significant challenge, particularly in urban environments where auditory traffic signals may be unavailable, inconsistent, or difficult to locate.

By detecting pedestrian traffic light states through computer vision, this project aims to serve as a foundational perception module that could be integrated into assistive applications such as mobile devices or wearable systems. While the present scope emphasizes detection accuracy and system design, the long-term vision is to contribute to safer and more inclusive smart city infrastructure.

---

## Dataset
The dataset used in this project was sourced from Roboflow:

**Pedestrian Traffic Lights**  
https://app.roboflow.com/test-xi95g/pedestrian-traffic-lights-final/2

The dataset consists of annotated images of pedestrian traffic lights and is organized into training, validation, and test splits. All annotations were exported in YOLO format via the Roboflow platform and used for model training and evaluation in this repository.

---

## Key Features
- Pedestrian traffic light detection using YOLOv8
- Support for image and video inference
- Real-time detection demonstration
- Jupyter notebooks for training, validation, and inference workflows

---

## Repository Structure
```
Pedestrian_Traffic_Light_Detection/
├── Inference.ipynb
├── Real_Time_Detection.ipynb
├── Train_Traffic_Light_Data.ipynb
├── Validation.ipynb
├── yolov8n.pt
├── runs/detect
├── README.md
└── LICENSE
```

---

## Evaluation
Model performance can be evaluated using standard object detection metrics such as precision, recall, and mean Average Precision (mAP). Validation workflows are provided in the included notebooks.

---

## Accessibility and Social Impact
This project is motivated by principles of accessibility and inclusive design. Although the repository currently provides a technical proof-of-concept for pedestrian traffic light detection, its broader goal is to support assistive technologies for visually impaired pedestrians.

Future extensions may include audio or haptic feedback systems, mobile or wearable deployment, and real-time navigation assistance tailored for accessibility use cases.

---

## Future Work
- Expand dataset diversity (lighting, weather, urban settings)
- Add support for additional signal types (e.g., countdown timers)
- Optimize for edge and mobile deployment
- Integrate feedback mechanisms for assistive applications

---

## License
This project is licensed under the **Apache-2.0 License**.

---

## Acknowledgements
- YOLOv8 by Ultralytics
- Pedestrian Traffic Lights dataset provided via Roboflow

---

## Author
Wonha Ryu
