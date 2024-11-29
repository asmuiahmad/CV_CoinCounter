# Coin Detection Using Python OpenCV

This project demonstrates how to use Python and OpenCV to detect and count coins in an image. 
The ```detect_coins``` function processes an input image, detects circular objects that resemble coins, and displays the count on the image.

## Features

- Convert images to grayscale for easier processing.
- Apply Gaussian blur to reduce noise.
- Use the Hough Circle Transform to detect circles (potential coins).
- Annotate detected coins on the image with circles and rectangles.
- Display the total coin count on the image.

## Requirements

To run this script, ensure the following Python libraries are installed:
- OpenCV (cv2)
- NumPy (numpy)
- Matplotlib (matplotlib)

Install the dependencies using pip:

```python
pip install opencv-python-headless numpy matplotlib
```

## Usage

1. Save the ```detect_coins``` function in a Python script (e.g., ```coin_detector.py```).
2. Replace the ```image_path``` with the ```path to your image```.

