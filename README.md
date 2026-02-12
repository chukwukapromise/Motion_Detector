Motion Detection using OpenCV (Python)

This project implements a simple **real-time motion detection system** using Python and OpenCV.
It detects movement by comparing consecutive video frames and highlighting moving objects with a bounding box.

## The system uses:

* Frame differencing
* Grayscale conversion
* Gaussian blur (noise reduction)
* Thresholding
* Contour detection

## Features

* Real-time webcam motion detection
* Highlights moving objects with a green bounding box
* Ignores small movements (noise filtering)
* Lightweight and easy to understand


## How It Works

1. Capture two consecutive frames from the webcam
2. Compute the absolute difference between them
3. Convert to grayscale
4. Apply Gaussian blur
5. Threshold the image
6. Detect contours
7. Draw bounding boxes around detected motion


## Future Improvements

* Background subtraction using MOG2
* Save motion timestamps
* Record video when motion is detected
* Deploy with CCTV
* Add object tracking.
