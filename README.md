# Hand-Tracking-Mouse-Controller

A Python-based application that uses computer vision to control the mouse cursor with hand gestures via a webcam. Built with OpenCV, MediaPipe, and PyAutoGUI, this project enables cursor movement, clicking, dragging, zooming, and scrolling through intuitive hand movements.

#Features
Cursor Movement: Move the mouse cursor by tracking the middle finger's MCP joint.
Left Click: Bend the index finger briefly to click; hold to drag.
Right Click: Bend the middle finger to perform a right click.
Double/Triple Click: Multiple quick index finger bends for double or triple clicks.
Dragging: Hold the index finger bent longer to drag.
Zoom: Toggle zoom mode with the pinky finger, then adjust with thumb-index distance.
Scroll: Toggle scroll mode with the ring finger, then scroll with thumb movement.
Smoothing: Smooth cursor movement for a natural feel.
Gesture Delay: 2-second delay after hand detection to prevent unintended actions.

#Prerequisites
Python 3.7 or higher
A webcam (built-in or external)

#How It Works:
Point your hand at the webcam with the palm facing the camera.
Wait 2 seconds after hand detection for gestures to activate.
Move your hand to control the cursor.
Use finger gestures as described in the "Features" section.
Exit: Press q while the webcam window is active to close the application.

Requirements
opencv-python: For webcam input and image processing.
mediapipe: For hand landmark detection.
pyautogui: For mouse and keyboard control.

Troubleshooting
Webcam Not Detected: Ensure your webcam is connected and not in use by another application.
Gestures Not Working: Adjust lighting or hand distance from the camera; tweak thresholds if needed.
Cursor Too Slow/Fast: Modify smoothing_factor or hand range variables.

Contributing
Feel free to fork this repository, submit issues, or create pull requests with improvements (e.g., new gestures, performance optimizations).
