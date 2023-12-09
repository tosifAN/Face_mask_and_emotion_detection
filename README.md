# YOLOv8 Face Mask Detection & Emotion Recognition

This project involves training a YOLOv8 object detection model for face mask detection and subsequently applying emotion detection (Happy, Sad, Neutral) on a separate dataset.

## Project Overview

- **Face Mask Detection:**
  - Trained a YOLOv8 model to detect face masks in images and videos.
  - Utilized a custom dataset with annotated face mask images for model training.

- **Emotion Recognition:**
  - Applied emotion detection (Happy, Sad, Neutral) on a different dataset.
  - Leveraged transfer learning techniques to classify emotions on faces detected by the YOLOv8 model.

## Project Structure

- `face_mask_detection/`: Contains code and model weights for face mask detection using YOLOv8.
- `emotion_recognition/`: Code and resources for emotion detection on a separate dataset.
- `datasets/`: Stored datasets used for face mask detection and emotion recognition tasks.
- `testing/`: Results and findings from testing both models on images and videos.

## Usage

1. **Face Mask Detection:**
   - Access the `face_mask_detection/` directory for code related to YOLOv8 training on face mask detection.
   - Train the model using the face mask dataset and save the trained weights.

2. **Emotion Recognition:**
   - Navigate to the `emotion_recognition/` directory for code related to emotion detection.
   - Apply emotion recognition on face crops obtained from the face mask detection model.

## Requirements

- Python 3.x
- YOLOv8 framework
- Face mask dataset (for face mask detection)
- Emotion dataset (for emotion recognition)
- Required libraries and dependencies

## Resources

- [Link to Face Mask Dataset (if publicly available)](face_mask_dataset_link)
- [Link to Emotion Dataset (if publicly available)](emotion_dataset_link)
- [Link to YOLOv8 Framework Documentation](yolov8_documentation_link)

## License

This project is licensed under the [License Name] License - see the [LICENSE](LICENSE) file for details.

## Contributors

- [Your Name]
- [Other Contributors, if applicable]
