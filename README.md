# Intelligent-NVR-cv
Intelligent NVR CV usually refers to a network video recorder that uses computer vision to automatically detect,classify , track or alert about things happening in the video.

Project 1.Webcam based
▪ This project utilizes opencv and mediapipe to detect human poses in 
real time.

▪ The goal of this project is to detect when a person appears in front of the webcam and tracking how long they stay there and also detecting multiple person with a timer at a time.

▪ A timer should start when a person is detected and stop when they leave.

▪ Features include:
- Pose estimation from a live webcam feed.
- Timer to track duration of detected pose.

How it works:

Project 2: Virtual Drawing Canvas
 
 A real-time interactive application that enables users to draw digitally on a virtual canvas using hand gestures tracked by a webcam feed.

- Functionalities:
  Users can draw lines, circles, rectangles, and freehand shapes.
Use specific gestures to select drawing modes, colors, or clear the canvas.

- Technical Specification:
  1.Computer Vision Techniques:
    -Hand landmark detection using MediaPipe Hands.
    -Gesture recognition based on detected finger positions.

 2.Libraries & Tools:
- OpenCV (camera feed, image processing).
- MediaPipe (hand tracking, landmark detection).
- NumPy (canvas management).
-
-  Workflow:
   1. Capture webcam feed and extract hand landmarks.
   2. Classify gestures based on landmark positions.
   3. Interpret gestures to draw shapes/colors on a virtual canvas overlay.
   4. Display the combined canvas and webcam feed in real-time.
