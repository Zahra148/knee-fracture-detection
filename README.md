# Knee X-ray Fracture Detection - Model Training

This repository contains the training code for a Knee X-ray Fracture Detection model using the **YOLO** object detection framework.  
The model is part of a Final Year Project (FYP) and is **not shipped** with pre-trained weights or datasets for privacy and size constraints.

## 📌 Features
- Uses **YOLO** from the [Ultralytics](https://github.com/ultralytics/ultralytics) library for object detection.
- Trains on custom Knee X-ray datasets.
- Integrated with **Gradio** for simple UI testing.
- Easily configurable for other datasets.

## ⚠️ Important
The dataset and trained model weights are **NOT included** in this repository.  
You must provide:
- Your own dataset (YOLO format).
- Your own trained model weights (if you want to run inference).

## 🛠 Requirements
See [`requirements.txt`](requirements.txt) for a full list of Python dependencies.

Install them with:
```bash
pip install -r requirements.txt

git clone https://github.com/Zahra148/knee-fracture-detection.git
cd knee-fracture-detection