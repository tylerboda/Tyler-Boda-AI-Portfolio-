Problem Statement

This project focuses on detecting and tracking objects in video using computer vision. The goal is to identify objects in each frame and track their movement over time, which is useful for applications like traffic monitoring, surveillance, and analytics.

Approach

In this project, I used a computer vision model to perform object detection and tracking. The process included:

Loading a video for analysis
Using a pre-trained model (such as YOLO) to detect objects
Tracking objects across frames using unique IDs
Analyzing object movement and behavior
Displaying results visually on video frames

This approach allows the system to not only detect objects but also follow them over time.

Results

Successfully detected objects in video frames
Tracked objects across multiple frames using IDs
Visualized bounding boxes and object movement
Generated counts and insights based on object behavior

Key Findings

Object tracking is more complex than detection because it requires consistency across frames
Lighting, speed, and occlusion can affect tracking performance
Real-time analytics can be built using detection + tracking
Models like YOLO are effective for fast and accurate detection

Technologies Used

Python
OpenCV
YOLO (Ultralytics)
NumPy
Matplotlib

How to Run

Open the notebook in Google Colab or Jupyter Notebook
Run all cells in order
Ensure internet connection for downloading models/videos
Adjust video path if needed
