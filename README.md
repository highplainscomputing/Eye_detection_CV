# Computer Vision Eye Detection

## Project Overview

This is a computer vision application that opens a webcam and detects eyes using the Haar Cascade Algorithm, along with the Hough Transform for improved results. 
The project is implemented in Python and relies on the following libraries: Python, NumPy, and OpenCV-Python.



## Table of Contents


- [Installation](#installation)
- [Usage](#usage)
- [Algorithm Overview](#algorithm-overview)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

  ## Algorithm Overview

### Haar Cascade Algorithm
The Haar Cascade Algorithm is a machine learning object detection method used to identify objects in images or video. In this project, it is utilized to detect eyes.

### Hough Transform
The Hough Transform is a technique used for the detection of simple shapes, such as lines or circles, in an image. In this project, it is used to improve the accuracy of eye detection.

### Why Haar Cascade, not CNN?
Haar cascades are a simpler and faster approach for object detection, while neural networks offer more flexibility and accuracy, but can be computationally expensive. 
The choice between the two approaches depends on the specific requirements of the task at hand, such as accuracy, speed, and available computing resources.
## Installation

To run this project on your local machine, follow these steps:

1. Create Virtual Environment
  ```bash
  python -m venv <your-environment-name>
```
Activate
```bash
<your-environment-name>\Scripts\activate
```
Deactivate
```bash
deactivate
```

2. Clone the repository:
```bash
git clone https://github.com/highplainscomputing/Eye_detection_CV.git
```

3. Install the required libraries:

```bash
pip install numpy opencv-Python
```
4. Run the application.
```bash
python eye_detector.py
```

## Usage
Provide instructions on how to use the application:

Launch the application, and it will open your webcam.
The application will start detecting eyes using the Haar Cascade Algorithm and Hough Transform.
Adjust parameters for better results (if applicable).

