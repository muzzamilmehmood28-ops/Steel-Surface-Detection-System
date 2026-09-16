# Steel-Surface-Detection-System
# Steel Surface Defect Detection using YOLOv8

An end-to-end computer vision project utilizing deep learning to automatically detect and classify surface defects on steel sheets. Built using **Ultralytics YOLOv8**, OpenCV, and Python, this model is designed for automated industrial quality control workflows.

---

## 🚀 Features

* **Automated Object Detection:** Detects industrial surface anomalies using state-of-the-art YOLOv8 architecture.
* **Data Augmentation:** Incorporates image augmentation pipelines (using Albumentations) to improve model robustness and generalization.
* **Google Colab Integration:** Fully configured to run and train seamlessly in cloud GPU environments like Google Colab.
* **Visualization & Evaluation:** Generates bounding-box predictions, confidence scores, and performance metrics (precision, recall, mAP).

---

## 🛠️ Tech Stack & Libraries

* **Language:** Python
* **Deep Learning Framework:** Ultralytics YOLOv8
* **Image Processing:** OpenCV (`opencv-python-headless`)
* **Data Handling:** NumPy, Pandas
* **Data Augmentation:** Albumentations
* **Visualization:** Matplotlib

---

## 📂 Project Structure

```text
steel-surface-defect-detection/
│
├── dataset/                    # Dataset directory (from github)
│   ├── train/
│   └── val/
├── runs/                       # Training results, weights, and metrics
├── Arbotrix_internship_Surface_defect_detection_project.ipynb # Main Colab notebook
└── README.md                   # Project documentation
