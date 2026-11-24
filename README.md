# Digital Twins: YOLO-Based Vehicle Detection and Tracking

Real-world traffic data collection and computer vision-based vehicle detection and tracking to support transportation planning and Digital Twin development. This project uses a traffic video recorded on Vassar Street, Cambridge, Massachusetts (MA).

## Study Area and Video Recording

A one-minute traffic video was recorded on Vassar Street, Cambridge, Massachusetts, to collect real-world traffic data.

## Methodology

### 1. Study Area and Video Recording
Selection of Vassar Street, Cambridge, Massachusetts, as the study area and recording of a one-minute traffic video for real-world data collection.

### 2. Frame Extraction and Dataset Creation
Extraction of video frames at two-second intervals, resulting in 30 images, and organization of the extracted frames into an image dataset.

### 3. Image Annotation and Class Definition
Annotation of the extracted images and definition of object classes for road-user detection and classification.

### 4. Dataset Partitioning
Division of the annotated dataset into training, validation, and testing subsets.

- Training: 60%
- Validation: 20%
- Testing: 20%

### 5. YOLO Model Training on the Mini-Dataset
Training a YOLO object-detection model using the prepared mini-dataset to detect and classify road users.

### 6. Vehicle Detection and Tracking using SimJamCV
Application of the trained YOLO model for vehicle detection and tracking using SimJamCV.

### 7. YOLO Model Performance Evaluation
Evaluation of the trained model using the following performance plots:

- F1–Confidence Curve
- Precision–Confidence Curve
- Precision–Recall Curve
- Recall–Confidence Curve
- Confusion Matrix
- Normalized Confusion Matrix

## Project Scope

The current project focuses on real-world video collection, dataset preparation, image annotation, YOLO model training, vehicle detection and tracking, and model performance evaluation. These steps provide a foundation for future transportation Digital Twin applications.

**Study Area:** Vassar Street, Cambridge, Massachusetts, USA.
