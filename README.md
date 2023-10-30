# Computer Vision Eye Detection

## Project Overview

This is a computer vision application that opens a webcam and detects eyes using the Haar Cascade Algorithm, along with the Hough Transform for improved results. The project is implemented in Python and relies on the following libraries: Python, NumPy, and OpenCV-Python.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Algorithm Overview](#algorithm-overview)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

## Installation

To run this project on your local machine, follow these steps:

1. Clone the repository:
```bash
git clone https://github.com/highplainscomputing/Eye_detection_CV.git
```

2. Install the required libraries:

```bash
pip install numpy opencv-Python
```
3. Run the application.
```bash
python eye_detector.py
```
## Usage
Provide instructions on how to use the application:

Launch the application, and it will open your webcam.
The application will start detecting eyes using the Haar Cascade Algorithm and Hough Transform.
Adjust parameters for better results (if applicable).

## Algorithm Overview

### Haar Cascade Algorithm
The Haar Cascade Algorithm is a machine learning object detection method used to identify objects in images or video. In this project, it is utilized to detect eyes.

### Hough Transform
The Hough Transform is a technique used for the detection of simple shapes, such as lines or circles, in an image. In this project, it is used to improve the accuracy of eye detection.
