Overview
This project aims to detect and identify trash in underwater environments using computer vision techniques. The system utilizes the YOLO (You Only Look Once) algorithm for object detection, allowing for real-time trash detection in aquatic areas. The goal is to aid in environmental conservation efforts by automating the identification of trash in underwater images.

Features
Real-time detection of various types of trash in underwater images.
Utilizes YOLO algorithm for accurate object detection.
Supports image preprocessing to enhance detection accuracy.
Technologies Used
Python: Main programming language.
TensorFlow: Framework for building and training machine learning models.
Keras: High-level API for neural networks in TensorFlow.
OpenCV: Library for computer vision and image processing.
YOLO: Object detection algorithm for real-time detection.
Clone this repository:
git clone https://github.com/PraganayakiTamilselvan/Underwater-trash-detection.git
Navigate to the project directory:
cd Underwater-trash-detection
Install the required Python packages:
pip install -r requirements.txt
Usage
Prepare your dataset or use the provided sample images.
Run the detection script:
python detect_trash.py
The script will process the images and output the detected trash objects with bounding boxes.
