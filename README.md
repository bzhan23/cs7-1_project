# Small target detection on an uncrewed surface vessel
The main purpose of the project is to complete the training of the target detection model, compare the target detection results in the MScoco dataset and the project dataset, and generate the final results and the best model.

## Table of contents

- [Introduction](#Introduction)
- [Install](#Install)
- [Instructions](#Instructions)

## Introduction

The project used DETR, Yolov5.Yolov8, MaskRCNN and FastRCNN to train and evaluate the mscoco and project datasets. YoloV8 was selected as the optimal model for the project.

- DETR (DEtection TRansformers) using PyTorch
- YOLOv5 using PyTorch
- YOLOv8 using PyTorch
- Mask R-CNN using Detectron2
- Fast R-CNN using Detectron2

## Install

### Environment Setup

Ensure you have Python 3.8+ installed. It's recommended to use a virtual environment.

### Environment Dependency

1.PyTorch

Follow the instructions from the PyTorch website to install the appropriate version for your system.

2.DETR

git clone https://github.com/facebookresearch/detr.git
cd detr
pip install -r requirements.txt
python setup.py build
python setup.py develop

3.YOLOv5

git clone https://github.com/ultralytics/yolov5.git
cd yolov5
pip install -r requirements.txt

4.YOLOv8

pip install ultralytics

5.Detectron2 (for Mask R-CNN and Fast R-CNN)

pip install detectron2 -f https://dl.fbaipublicfiles.com/detectron2/wheels/cu113/torch1.10/index.html
