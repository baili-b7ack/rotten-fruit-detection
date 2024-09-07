
# YOLO Implementations with Weighted Box Fusion (WBF) for Rotten Fruit Detection

This repository contains experiments from my thesis project, where I evaluate different versions of YOLO models combined with Weighted Box Fusion (WBF) to compare their performance in object detection tasks. The models evaluated in this project include:

1. **YOLOv8 with WBF**
2. **GOLD YOLO with WBF**
3. **YOLOv6 3.0 with WBF**

## Project Structure

The project is organized as follows:

- **THESIS_Experiment_YOLOV8_WBF.ipynb**: Implements and evaluates YOLOv8 with WBF.
- **THESIS_Experiment_GOLD_YOLO_WBF.ipynb**: Implements and evaluates GOLD YOLO with WBF.
- **THESIS_Experiment_YOLOV6_V3.0_WBF.ipynb**: Implements and evaluates YOLOv6 3.0 with WBF.
- **Evaluation_WBF_Thesis.ipynb**: A notebook that compiles the evaluation results from all the experiments and compares their performance.

## Methodology

- **YOLOv8**: A state-of-the-art real-time object detection model, which is known for its speed and accuracy.
- **GOLD YOLO**: A refined version of YOLO designed for specific tasks or datasets.
- **YOLOv6 3.0**: Another variant of YOLO optimized for efficiency and performance.

All these models are enhanced using **Weighted Box Fusion (WBF)**, which combines the bounding boxes from multiple detections to improve the final output by reducing noise and improving accuracy.

## Evaluation Metrics

The models are evaluated using the following metrics:
- **mAP (mean Average Precision)**
- **Precision**
- **Recall**

## Results

The final evaluation results are detailed in the `Evaluation_WBF_Thesis.ipynb` notebook. The purpose of these evaluations is to determine which model performs best in terms of accuracy and efficiency for object detection tasks.
