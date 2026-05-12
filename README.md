# Kidney-Stone-Detection-from-CT-Scan-Images-using-a-Hybrid-of-Vision-Transformer-and-YOLOv8
Hybrid deep learning repository for kidney stone detection from CT scan images using a Vision Transformer backbone with YOLOv8 style detection and ablation experiments for backbone size, augmentation, input resolution, and loss weights.
This repository contains the code and dataset structure for kidney stone detection from CT scan images using a hybrid Vision Transformer and YOLOv8 based approach. The method is built around ViTBackedYOLOv8, which replaces the standard YOLOv8 convolutional backbone with a pretrained Vision Transformer so that global context and local detection cues are combined in one framework. The manuscript reports that the dataset contains 1,300 annotated CT images, expanded to 5,486 samples through augmentation, and that the proposed model achieved strong detection results on the test set, including mAP@0.5 of 0.9878, precision of 0.9904, recall of 0.9883, F1-score of 0.983, and accuracy of 98.3%. 

## Project Structure

```text
Kidney Stone Detection from CT Scan Images using a Hybrid of Vision Transformer and YOLOv8/
├── code/
│   ├── ViTBackedYOLOv8.ipynb
├── data/
│   ├── train/
│   │   ├── images/
│   │   └── labels/
│   ├── valid/
│   │   ├── images/
│   │   └── labels/
│   └── test/
│       ├── images/
│       └── labels/
└── README.md
