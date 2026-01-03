# 📦 CodeAlpha – Object Detection and Tracking
## 📌 Project Overview

This project implements real-time object detection and tracking using the YOLOv8 deep learning model. It is designed to detect multiple objects in live video streams, recorded videos, or images with high accuracy and efficiency. The solution is suitable for applications such as video surveillance, intelligent monitoring systems, and computer vision research.

# 🚀 Key Features

🔍 Object Detection using pretrained YOLOv8 weights (yolov8n.pt)

🎥 Real-Time Object Tracking across video frames

📦 Bounding Boxes with Class Labels

⚡ Optimized Performance for speed and accuracy

🧩 Easily Extensible for custom datasets and use cases

## 🛠️ Installation & Setup

1️⃣ Clone the Repository
~~~
git clone https://github.com/ashishraj-hub/CodeAlpha_Object-Detection-and-Tracking.git
cd CodeAlpha_Object-Detection-and-Tracking
~~~

2️⃣ Install Required Dependencies
~~~
pip install -r requirements.txt
~~~
3️⃣ System Requirements

*Python 3.8 or higher*

GPU support is optional but recommended for better performance
~~~
📂 Project Structure

CodeAlpha_Object-Detection-and-Tracking/
│── Object_Detection.py   # Main script for object detection & tracking
│── yolov8n.pt            # Pretrained YOLOv8 model weights
│── README.md             # Project documentation
│── LICENSE               # License information
~~~
## ▶️ How to Run the Project

Execute the main script:

python Object_Detection.py

You can customize the script to:

Use a webcam for live detection

Process video files

Perform detection on static images

## 📸 Output Preview

Objects are detected and tracked in real time

Bounding boxes and class labels are displayed dynamically on each frame

📖 Dependencies Used

Python 3.8+

Ultralytics YOLOv8

OpenCV

NumPy

## 📜 License

This project is licensed under the MIT License.
Refer to the LICENSE file for more details.

# 🤝 Contributing Guidelines

Contributions are welcome and appreciated!

Fork the repository

Create a new feature branch

Commit your changes

Open a pull request
