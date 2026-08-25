# 🦴 Bone Fracture Detection & Segmentation

## 📌 Overview

A deep learning project that detects and segments **bone fractures from X-ray images** using **YOLOv8 Segmentation**.

## 🎯 Objective

* Detect bone fractures from X-ray images
* Identify the fracture location using segmentation
* Train and evaluate a YOLOv8 model

## 🛠️ Technologies

* Python
* YOLOv8 (Ultralytics)
* PyTorch
* OpenCV
* NumPy
* Pandas
* Matplotlib
* Scikit-learn

# 📌 Project Structure
<pre>
Bone-Fracture-Detection/
├── fracture.ipynb
├── requirements.txt
├── README.md
├── dataset/
│   └── FracAtlas/
├── yolo_dataset/
│   ├── images/
│   │   ├── train/
│   │   └── val/
│   ├── labels/
│   │   ├── train/
│   │   └── val/
│   └── data.yaml
└── runs/
    └── segment/
        └── train/
</pre>

## 📊 Dataset

**FracAtlas Dataset**

The COCO-format annotations are converted into **YOLO format** and divided into:

* 80% Training
* 20% Validation

## 🤖 Model

**YOLOv8m-Seg**

* Image Size: 416 × 416
* Epochs: 30
* Batch Size: 4
* Optimizer: AdamW
* Learning Rate: 0.001

## 🔄 Workflow

```text
X-Ray Images
     ↓
COCO Annotations
     ↓
COCO → YOLO Conversion
     ↓
Train / Validation Split
     ↓
YOLOv8 Segmentation
     ↓
Fracture Detection & Segmentation
```

## 🚀 How to Run

```bash
pip install -r requirements.txt
jupyter notebook
```

Open:

```text
fracture.ipynb
```

Run the notebook cells in order.

## 📁 Main Files

```text
fracture.ipynb      # Project notebook
requirements.txt    # Dependencies
README.md           # Project documentation
```

## ⚠️ Disclaimer

This project is for **educational and research purposes only** and is not intended for medical diagnosis.

# Author
Sowmiya E

Btech CSE AI & DS
