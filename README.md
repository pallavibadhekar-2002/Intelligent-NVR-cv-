# Intelligent-NVR-cv


Project 2: Virtual Drawing Canvas
Overview: A real-time interactive application that enables users to draw digitally on a virtual canvas using hand gestures tracked by a webcam feed.
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
- Workflow:
   1. Capture webcam feed and extract hand landmarks.
   2. Classify gestures based on landmark positions.
   3. Interpret gestures to draw shapes/colors on a virtual canvas overlay.
   4. Display the combined canvas and webcam feed in real-time.
