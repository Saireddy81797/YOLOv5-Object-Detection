# Object Detection using YOLOv5 on Custom Dataset

## 📌 Overview
This project implements an **object detection model** using **YOLOv5** trained on a custom dataset.  
It is designed for **classification and sorting tasks in the sustainability sector**.

## ⚙️ Tech Stack
- Python
- PyTorch
- YOLOv5
- OpenCV
- Custom Dataset (Garbage Classification / COCO128)

## 🚀 Features
- Real-time object detection using YOLOv5.
- Preprocessing and augmentation of custom dataset.
- Transfer learning with pretrained weights (`yolov5s.pt`).
- Evaluation using **mAP, Precision, Recall**.

## 📊 Training Command
```bash
python train.py --img 416 --batch 16 --epochs 10 --data custom.yaml --weights yolov5s.pt --name yolo_custom
