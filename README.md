
# 🍎 YOLO Implementations with Weighted Box Fusion (WBF) for Rotten Fruit Detection

This repository contains the results from my thesis project, where I implemented and compared different versions of the YOLO (You Only Look Once) object detection models combined with **Weighted Box Fusion (WBF)** to improve accuracy in detecting rotten fruits. The models evaluated in this project are:

- **YOLOv8 with WBF**
- **GOLD YOLO with WBF**
- **YOLOv6 3.0 with WBF**

## 🚀 Project Structure

The project is divided into the following key notebooks:

| Notebook | Description |
|----------|-------------|
| `THESIS_Experiment_YOLOV8_WBF.ipynb` | Implements and evaluates YOLOv8 combined with WBF. |
| `THESIS_Experiment_GOLD_YOLO_WBF.ipynb` | Implements and evaluates GOLD YOLO combined with WBF. |
| `THESIS_Experiment_YOLOV6_V3.0_WBF.ipynb` | Implements and evaluates YOLOv6 3.0 combined with WBF. |
| `Evaluation_WBF_Thesis.ipynb` | Compiles and compares the performance of all models. |

## 🛠️ Methodology

### Models Used
- **YOLOv8**: A highly efficient real-time object detection model, offering the latest advancements in the YOLO series.
- **GOLD YOLO**: A specialized variant of YOLO tailored for particular datasets and tasks.
- **YOLOv6 3.0**: A further optimized version of YOLO focusing on both performance and computational efficiency.

### Enhancement: **Weighted Box Fusion (WBF)**
WBF is used to merge overlapping bounding boxes from multiple detection models, increasing the accuracy of the final output by reducing redundant detections and false positives.

---

## 📊 Evaluation Metrics

The models are evaluated based on the following key metrics:

- **mAP (mean Average Precision)**: Measures the accuracy of the object detection model.
- **Precision**: The proportion of positive identifications that are actually correct.
- **Recall**: The proportion of actual positives that were correctly identified.

---

## 📈 Results

Detailed evaluation results are available in the [`Evaluation_WBF_Thesis.ipynb`](./Evaluation_WBF_Thesis.ipynb) notebook. The goal of this thesis is to identify which model performs best in terms of **accuracy** and **efficiency** for detecting rotten fruits in various conditions.
