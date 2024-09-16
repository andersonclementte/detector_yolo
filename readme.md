# Vehicle Detection and Counting using YOLOv5

This project is a vehicle detection and counting system using the YOLOv5 model. It uses a pre-trained model to detect various types of vehicles in a video file and stores the detected counts for analysis. The script is implemented in a Jupyter Notebook and uses the YOLOv5 model to detect objects in a given video. The results are saved, and video processing, vehicle counting, and result visualization are implemented in this project.

## Features
- Vehicle detection in a video using a YOLOv5 model.
- Counting detected vehicles of different classes.
- Visualization of detection results.
- Saving processed video with vehicle detections.

## Prerequisites
- Python 3.9+
- CUDA-compatible GPU (for running YOLOv5 on GPU)
- Jupyter Notebook (if you prefer running the script interactively)

### Python Packages

The following Python packages are required:
- `torch`
- `opencv-python`
- `yolov5` (installable from the official YOLOv5 GitHub repository)
- `numpy`
- `ipython`


## Running

 - 1. Clone the repository
 - 2. Prepare the Jupyter Notebook
 - 3. Run all jupyter cells