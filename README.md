# Car-Detection-with-YOLO
This project implements a car detection system using YOLO (You Only Look Once), a real-time object detection system. The YOLO model is employed for accurate and efficient detection of cars in images and videos.

## Required libraries

1. tensorflow
2. pandas
3. os
4. keras
5. PIL
6. numpy
7. argparse
8. matplotlib
9. scipy
10. yad2k (Yet Another DarkNet 2 Keras)- to import YOLO

## Working
### 1. Installing Packages
Ensure you have the required packages installed.

### 2. yolo_filter_boxes
The yolo_filter_boxes module is responsible for filtering bounding boxes predicted by the YOLO model. This step ensures that only relevant and accurate bounding boxes around cars are retained.

### 3. Non-max Suppression using IoU (Intersection over Union)
Non-max suppression is employed to eliminate redundant bounding boxes by comparing their Intersection over Union (IoU). This step helps in keeping the most relevant and non-overlapping bounding boxes.

### 4. yolo_non_max_suppression
The yolo_non_max_suppression script implements non-max suppression using IoU. Execute this script to perform non-max suppression on the filtered bounding boxes.

### 5. yolo_eval
The final step involves evaluating the YOLO model's performance on car detection. The yolo_eval script calculates precision, recall, and F1 score based on the ground truth and predicted bounding boxes.

## Usage
1. Install dependencies:
2. Download the pre-trained YOLO weights and place them in the weights directory.
3. Execute the steps mentioned above for filtering boxes, non-max suppression, and evaluation.

## Acknowledgments
Special thanks to the YOLO project for providing a powerful and efficient object detection model.

Feel free to reach out for any questions or improvements!
