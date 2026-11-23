# Harris-Corner-Detection-OpenCV---BSCY-4388-Computer-Vision
Harris Corner Detection using Python and OpenCV for image and video processing.

## Project Overview
This project implements the Harris Corner Detection algorithm using Python and OpenCV for image and video processing.

The objective is to identify important corner points in images and video frames using computer vision techniques.

## Lab 1: Image Processing
- Load the original image.
- Convert the image to grayscale.
- Apply Harris Corner Detection.
- Dilate detected corners.
- Apply a threshold to filter weak corners.
- Draw red circles around detected corners.

## Lab 2: Video Processing
- Load a video using OpenCV.
- Process the video frame by frame.
- Convert each frame to grayscale.
- Apply Harris Corner Detection.
- Draw red circles around detected corners.
- Save the processed video.

## Technologies Used
- Python
- OpenCV
- NumPy
- Google Colab

## Parameters
| Parameter | Value |
|---|---|
| blockSize | 2 |
| apertureSize | 3 |
| k | 0.04 |
| Threshold | 0.1 * dst.max() |

## Project Structure
- harris_corner_detection_image.py
- harris_corner_detection_video.py
- images/
- README.md
- requirements.txt

## Installation
Install the required libraries:

```bash
pip install -r requirements.txt
```

## Requirements
- Python 3
- OpenCV
- NumPy

## Results
Screenshots of the original and processed images and video frames are included in the images folder.

## Author
Computer Science – Artificial Intelligence
