# Real-Time-Face-Blur-Using-MediaPipe-OpenCV
This project uses MediaPipe Face Detection and OpenCV to automatically detect faces in images and blur them for privacy protection. It supports both single-image processing and real-time webcam blurring, making it useful for anonymizing faces in videos, streams, or personal photos.

✨ Features

🔍 Detects faces using MediaPipe FaceDetection

🟦 Applies Gaussian blur to all detected faces

🖼 Works on images (--mode image)

🎥 Works in real-time webcam mode (--mode webcam)

💾 Saves processed output (for image mode)

⚡ Fast & lightweight

🛠 Tech Stack

Python 3

OpenCV

MediaPipe

argparse

How It Works

Frame is captured (image or webcam)

Converted to RGB and passed to MediaPipe

Face bounding boxes are extracted

Each face region is blurred using OpenCV

Output is displayed (and saved in image mode)
