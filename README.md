# vehicle_speed_estimator-using-python
This Python project detects vehicles in a video using the YOLOv8 object detection model and estimates their speed based on their movement between frames. It’s a practical demonstration of real-time vehicle tracking and rough speed approximation using computer vision.
# 🎯 Features
-Detects and tracks vehicles (default: cars) in video

-Estimates speed in km/h using bounding box displacement

-Annotates bounding boxes with speed and object IDs

-Uses YOLOv8 from Ultralytics

-Works on pre-recorded video footage
# 🛠 Requirements
-Python 3.8+

-Ultralytics YOLO

-OpenCV

-NumPy
# Install dependencies:

-pip install ultralytics opencv-python
# ▶ How to Run
-Clone this repository.

-Place a sample vehicle video in the project folder and update the path in vehicle_speed.py.

-Run the script:

-python vehicle_speed.py
-Press q to stop the video.
