# Project: Object Detection Using YOLOv4

**Object Detection Using YOLOv4** is a computer vision project that uses the YOLOv4 (You Only Look Once) deep learning model for real-time object detection. The system captures video from a webcam, processes each frame, and detects objects within the scene, displaying bounding boxes and class labels on the detected objects. This project is aimed at demonstrating the power of YOLOv4 in recognizing and classifying objects in real-time.

### Features
- Real-time object detection with YOLOv4.
- Detection of multiple objects in a single frame.
- Display of bounding boxes and confidence scores for each detected object.
- Support for detecting a wide range of objects from the COCO dataset, including people, animals, vehicles, and everyday objects.

### Requirements
- Python 3.x
- OpenCV (`opencv-python`)
- NumPy
- YOLOv4 weights, configuration file, and COCO class labels file

### Installation Instructions

1. **Install Dependencies**:
    - Ensure that Python 3.x is installed.
    - Install required Python libraries:
      ```bash
      pip install opencv-python numpy
      ```

2. **Running the Script**:
    - Place the `yolov4.weights`, `yolov4.cfg`, and `coco.names` files in the same directory as the script.
    - Run the Python script:
      ```bash
      python object_detection_yolov4.py
      ```

3. **Exit the Program**:
    - To exit the object detection window, press `q`.
