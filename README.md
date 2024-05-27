# Helmet-and-Number-Plate-Detection
Detects Helmet and Number plate of a vehicle


```markdown
# Object Detection and Helmet Recognition

This repository contains code for object detection using YOLOv3 and helmet recognition using a pre-trained CNN model. The system processes a video stream, detects objects, and identifies whether a person in the frame is wearing a helmet or not.

## Table of Contents

- [Requirements](#requirements)
- [Setup](#setup)
- [Usage](#usage)
- [Results](#results)
- [License](#license)

## Requirements

- Python 3.x
- OpenCV
- NumPy
- imutils
- TensorFlow
- CUDA Toolkit (for GPU acceleration)

## Setup

1. Clone the repository:

   ```bash
   git clone https://github.com/yourusername/yourrepository.git
   cd yourrepository
   ```

2. Download the YOLOv3 weights file (`yolov3-custom_7000.weights`) and configuration file (`yolov3-custom.cfg`). Place them in the root directory.

3. Download the pre-trained helmet detection model (`helmet-nonhelmet_cnn.h5`) and place it in the root directory.

4. Ensure all dependencies are installed:

   ```bash
   pip install opencv-python numpy imutils tensorflow
   ```

## Usage

1. Run the script:

   ```bash
   python main.py
   ```

2. The script will process a video file (`video.mp4`), perform object detection, and output a new video (`output.avi`) with bounding boxes around detected objects and labels indicating helmet or no-helmet.

## Results

The `output.avi` file will contain the processed video with object detection and helmet recognition visualized.


