# 🐾 Object Detection with YOLOv8 & Supervision

A quick-start Python implementation for detecting objects (like cats and dogs) using **Ultralytics YOLOv8** and visualizing bounding boxes with **Roboflow Supervision**.

---

## 📌 Overview

This project demonstrates how to:
- Load a pre-trained **YOLOv8** model (`yolov8n.pt`).
- Run object detection on an image.
- Parse detection results into **Supervision** format.
- Draw clean, styled bounding boxes and confidence labels.
- Render the annotated image directly in a Jupyter Notebook / Google Colab / IDE.

---

## 🛠️ Prerequisites & Installation

Ensure you have Python installed, then install the required dependencies:

```bash
pip install ultralytics supervision opencv-python matplotlib
