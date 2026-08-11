# Object Detection Using Transfer Learning

## Project Overview

This project explores object detection using transfer learning and a pretrained computer vision model.

Unlike basic image classification, object detection identifies both what objects are present and where those objects appear within an image.

## Problem Statement

Training an object detection model completely from scratch can require large datasets and significant computing resources.

Transfer learning allows an existing pretrained model to reuse visual knowledge it has already learned and apply it to a new computer vision task.

## Approach

The project uses a pretrained object detection model to analyze images and generate object-level predictions.

The workflow includes:

- Loading a pretrained model
- Preparing image inputs
- Running object detection
- Identifying detected object classes
- Reviewing confidence scores
- Visualizing detections and bounding boxes
- Evaluating model behavior on test images

## Technologies Used

- Python
- Google Colab
- Transfer Learning
- Pretrained Computer Vision Models
- Object Detection
- Image Processing

## Dataset and Pretrained Model

This project uses pretrained **Ultralytics YOLO11** models for object detection and segmentation.

The pretrained models were trained on the **COCO (Common Objects in Context) dataset**, which contains 80 common object categories.

The full COCO dataset is not stored in this GitHub repository.

**COCO Dataset:**  
https://cocodataset.org/

The YOLO model weights are downloaded automatically by Ultralytics when the model is loaded for the first time. The notebook then runs the pretrained model on sample and test images.

No manual download of the full COCO dataset is required to run the object detection portion of this notebook.## Results

The completed notebook contains the object detection results generated during the lab, including predictions and visual outputs.

The model demonstrates how transfer learning can provide useful object detection capabilities without requiring a model to be trained completely from scratch.

## Key Findings

This project helped me understand the difference between image classification and object detection.

Classification answers what an image represents, while object detection can identify multiple objects and locate them within the same image.

I also gained experience working with pretrained models and understanding why transfer learning is useful when training data or computing resources are limited.

## How to Run

1. Open the `.ipynb` notebook in Google Colab.
2. Run the installation and import cells.
3. Load the pretrained model.
4. Load or upload the test images.
5. Run object detection.
6. Review the predicted classes, confidence scores, and visual outputs.
