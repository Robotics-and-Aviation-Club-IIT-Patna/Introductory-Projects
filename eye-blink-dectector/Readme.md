# Face and Eye Detection with OpenCV

This Python script utilizes OpenCV to detect faces and eyes in real-time using the webcam feed. If two eyes are detected within a face region, the user can press 's' to begin. 

## Prerequisites

Make sure you have Python installed on your system along with OpenCV library. You can install OpenCV using pip:


## Usage

1. Clone this repository or download the script `face_eye_detection.py`.
2. Ensure that the haarcascade XML files (`haarcascade_frontalface_default.xml` and `haarcascade_eye_tree_eyeglasses.xml`) are in the same directory as the script.
3. Run the script using Python:


4. A window will open displaying the webcam feed. Position yourself in front of the camera.
5. If your face is detected and at least two eyes are found, a message will prompt you to press 's' to begin.
6. Press 's' to start the game .

## Files

- `face_eye_detection.py`: Python script for face and eye detection.
- `haarcascade_frontalface_default.xml`: Pre-trained Haar cascade file for detecting faces.
- `haarcascade_eye_tree_eyeglasses.xml`: Pre-trained Haar cascade file for detecting eyes.
- `README.md`: This file.

## Dependencies

- Python 3.x
- OpenCV

