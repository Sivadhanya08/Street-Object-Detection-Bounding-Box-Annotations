Street Object Detection Annotation (CVAT)

This document describes the annotation work completed for a Street Object Detection Dataset using CVAT (Computer Vision Annotation Tool).
The objective of this project is to label street-level objects for computer vision and object detection tasks.

Project Overview

The dataset consists of street surveillance footage where multiple object classes were annotated using bounding boxes.
Annotations were created manually in CVAT to ensure high-quality, frame-accurate labeling.

This dataset can be used for:

* Object Detection
* Traffic Analysis
* Smart City Applications
* Autonomous Vehicle Research
* Computer Vision Model Training

Annotated Object Classes
The following classes were labeled:

* Car
* Bike
* Truck
* Pedestrian
  
Annotation Tool Used

Tool: CVAT – Computer Vision Annotation Tool
Annotation Type: Bounding Boxes
Export Formats:
* Pascal VOC (XML)
* COCO JSON
* YOLO TXT
* CVAT XML
  
Repository Structure
Street_Object_Detection_Annotation/
│
├── annotations/               
│
├── dataset/                   
│
└── README.md                  

Usage
This is an annotation-only project, so no installation or special setup is required.
You can download the annotation files and use them directly in:
* YOLOv5 / YOLOv8
* TensorFlow Object Detection
* PyTorch / Detectron2
* OpenCV pipelines
* Custom ML training workflows
  
Future Enhancements
* Add segmentation masks
* Add more diverse weather/time conditions
* Increase dataset size
* Train a YOLO model using these annotations and upload results
* Add validation scripts or notebook

License This project is open-source under the MIT License. You are free to use, modify, and distribute it for educational or research purposes.

Author Sivadhanya S Computer Science and Engineering Student Email: sivadhanya5757@gmail.com LinkedIn: www.linkedin.com/in/sivadhanya-s-432a7425a GitHub: GitHub: https://github.com/Sivadhanya08/Street-Object-Detection-Bounding-Box-Annotations
