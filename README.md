# YOLOv8 Face Mask Detection & Emotion Recognition

This project involves training a YOLOv8 object detection model for face mask detection and subsequently applying emotion detection (Happy, Sad, Neutral) on a separate dataset.

## Project Overview

- **Face Mask Detection:**
  - Trained a YOLOv8 model to detect face masks in images and videos.
  - Utilized a dataset with face mask images for model training.

- **Emotion Recognition:**
  - Applied emotion detection (Happy, Sad, Neutral) on a different images.
  - Leveraged transfer learning techniques to classify emotions on faces detected by the YOLOv8 model.

## Project Structure

- `part1/`: Contains code and model weights for face mask detection using YOLOv8.
- `part2/`: Code and resources for emotion detection on a separate dataset.
- `source and result/`: Results and findings from testing both models on images and videos.

## Usage

1. **Face Mask Detection:**
   - Access the `part1/` directory for code related to YOLOv8 training on face mask detection.
   - Train the model using the face mask dataset and save the trained weights.

2. **Emotion Recognition:**
   - Navigate to the `part2/` directory for code related to emotion detection.
   - Apply emotion recognition on face crops obtained from the face mask detection model.

## Requirements

- Python 3.x
- YOLOv8 framework
- Face mask dataset (for face mask detection)
- Emotion dataset (for emotion recognition)
- Required libraries and dependencies

## Resources

- https://www.kaggle.com/datasets/omkargurav/face-mask-dataset(face_mask_dataset_link)
- https://www.kaggle.com/datasets/jonathanoheix/face-expression-recognition-dataset(emotion_dataset_link)
- https://docs.ultralytics.com/(yolov8_documentation_link)

