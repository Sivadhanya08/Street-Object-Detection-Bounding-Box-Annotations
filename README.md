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
