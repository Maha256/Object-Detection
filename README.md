# Object-Detection
# 🧠 Simple Object Detection with PyTorch

This is a beginner-friendly object detection project built using **PyTorch** and run in **Google Colab**. The goal is to detect objects in images and draw bounding boxes around them. The dataset was sourced from **Kaggle**.

---

## 📂 Dataset

- Sourced from: [Kaggle](https://www.kaggle.com/](https://www.kaggle.com/datasets/kkhandekar/object-detection-sample-images/code))  
- The dataset contains images with **no bounding box labels**.
- The model is trained/inferred to detect **any object** that differs from the background (no class-specific labels).

---

## 🛠️ Tools & Libraries

- Python
- PyTorch (Torchvision’s pre-trained Faster R-CNN)
- OpenCV (`cv2`) for drawing bounding boxes
- Matplotlib for visualization
- Google Colab for development

---

## 📌 What This Project Does

- Loads and preprocesses 10 images from the dataset
- Uses a pre-trained **Faster R-CNN** model for inference
- Converts predictions into bounding boxes
- Draws the bounding boxes on the original images
- Displays all annotated images

> Note: Since the dataset doesn’t include ground truth annotations, **AUROC or accuracy metrics are not computed**.

---

## 📸 Sample Output

Bounding boxes are drawn around detected objects with their predicted class label and confidence score.

---
## 🚀 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/Maha256/Object-Detection.git
