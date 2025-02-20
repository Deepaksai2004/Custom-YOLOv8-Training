# Custom-YOLOv8-Training
This repository contains a custom YOLO object detection model trained to detect buildings, cars, and trees using a labeled dataset. It includes dataset preparation, YAML configuration, training scripts, and model-saving techniques using Google Colab. The project utilizes YOLO for high-accuracy object detection and supports easy deployment.

📂 Dataset Structure
Your dataset should follow this structure:

/Dataset_name
│── images
│   ├── train  (training images)
│   ├── test   (validation images)
│── labels
│   ├── train  (corresponding label files)
│   ├── test   (corresponding label files)
│── dataset.yaml  (dataset configuration file)

