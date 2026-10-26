# forest-fire-detection-yolov8
Forest fire detection using YOLOv8 and computer vision

# Forest Fire Detection Using YOLOv8

## Project Overview
This project uses YOLOv8 object detection to identify possible fire regions in images.

## Technologies Used
- Python
- YOLOv8
- Roboflow
- Google Colab
- PyTorch
- Gradio

## Project Workflow
1. Obtain a fire image dataset from Roboflow.
2. Prepare the dataset in YOLOv8 format.
3. Train a pretrained YOLOv8s model for 20 epochs.
4. Evaluate the trained model.
5. Test the model using uploaded images.
6. Create a Gradio frontend for image upload and fire detection.

## Validation Results
- Precision: 90.4%
- Recall: 78.5%
- mAP@50: 68.3%
- mAP@50–95: 55.6%

## Limitations
This is an experimental prototype. Predictions may be incorrect, and further model evaluation and improvement are required before real-world use.

## Future Improvements
- Verify and improve dataset labels.
- Improve detection performance.
- Evaluate the model on an independent test set.
- Explore real-time fire detection.
