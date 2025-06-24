# Parking-slot-detection-using-Computer-Vision

🚗 Parking Spot Detection using OpenCV
This project implements an intelligent parking monitoring system that detects vacant and occupied parking spots from video footage using image processing techniques in OpenCV.

📹 Demo
The system processes a video stream (.mp4) of a parking lot and overlays bounding boxes on each parking spot:

🟩 Green for available spots

🟥 Red for occupied spots

It also displays the total number of available parking spots in real time.

🧠 Key Features
Dynamic difference-based frame comparison for spot change detection

Efficient processing using frame skipping (adjustable via step)

Parking spot segmentation from a binary mask

Modular design using helper functions (util.py)
