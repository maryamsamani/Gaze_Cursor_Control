# Eye Tracking and Cursor Control

This repository is an implementation of eye tracking system for cursor control purposes using computer vision. The code utilizes the OpenCV library along with dlib's face detection and shape prediction models to track the eyes and determine the movement of the cursor based on the gaze direction.

# Features
1. Real-time eye tracking: The code tracks the position of the eyes in a live video feed from a webcam.
2. Blink detection: It detects blinks by analyzing the eye aspect ratio, which measures the opening and closing of the eyes.
3. Gaze detection: The code determines the direction of the gaze (left, right, up, or down) based on the position of the eyes.
4. Scroll control: By blinking, the user can enable or disable scrolling functionality.
5. Mouse control: The code allows the user to perform mouse clicks by detecting blinks.

# Prerequisites
1. Python 3.x
2. OpenCV library
3. dlib library
4. imutils library
5. pyautogui library
6. shape_predictor_68_face_landmarks.dat (can be downloaded [Link 1](http://dlib.net/files/?C=N;O=D) or [Link 2](https://www.kaggle.com/datasets/sergiovirahonda/shape-predictor-68-face-landmarksdat))

