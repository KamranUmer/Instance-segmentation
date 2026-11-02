<div align="center">

# 🧩 Instance Segmentation · YOLOv7

**A clean, reusable template for training YOLOv7 instance segmentation on your own dataset.**

<img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python"> <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white" alt="PyTorch"> <img src="https://img.shields.io/badge/YOLO-111F68?style=for-the-badge" alt="YOLO"> <img src="https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white" alt="Jupyter">

<a href="https://colab.research.google.com/github/KamranUmer/Instance-segmentation/blob/main/yolov7_instance_segmentation_on_custom_data.ipynb"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open in Colab"></a>

</div>

<p align="center"><img src="https://github.com/KamranUmer/Instance-segmentation/assets/86089489/44cb0bc2-cb09-4d1e-9c33-03b46118c8c4" alt="Instance Segmentation · YOLOv7 screenshot" width="85%"></p>

## 📌 Overview

The base workflow behind my YOLOv7 segmentation projects (MRI tumors, grass): run the pre-trained COCO model, convert your data to the required format, train on Colab, and evaluate box and mask metrics.

## 🔬 Pipeline

- Inference with the pre-trained COCO segmentation model
- Required data format explained
- Custom training (150 epochs)
- Evaluation and result visualisation

## 📊 Results

| Metric | Value |
|---|---|
| Mask mAP@0.5 | 0.995 |
| Mask mAP@0.5:0.95 | 0.847 |

> Small demo validation set (3 images).

## 🚀 Getting Started

```bash
# Open the notebook in Google Colab (badge above), choose a GPU runtime,
# then run the cells from top to bottom.
```

## 🙏 Acknowledgements

- [YOLOv7](https://github.com/WongKinYiu/yolov7) by WongKinYiu et al.

---

<div align="center">

Built by <a href="https://github.com/KamranUmer"><b>Kamran Umer</b></a> · ⭐ Star the repo if you find it useful

</div>
