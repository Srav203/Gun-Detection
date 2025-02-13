# Gun-Detection
Gun Detection using OpenCV

This project detects guns in a live video stream using OpenCV and Haar Cascade classifiers. The system processes video frames, converts them to grayscale, and applies object detection to identify guns in real-time.


---

Features 

Real-time gun detection using Haar Cascade classifiers.

Draws bounding boxes around detected guns.

Live video stream processing using OpenCV.

Exits detection on pressing 'q'.



---

Requirements

Ensure you have the following installed:

Python 3.x

OpenCV

NumPy

imutils



---

Installation

1. Clone the Repository

git clone https://github.com/Srav203/Gun-Detection.git
cd Gun-Detection

2. Install Dependencies

pip install opencv-python numpy imutils


---

Usage

1. Run the Script

python gun-detection.py

2. How It Works

The webcam captures real-time video.

The system detects guns and highlights them with blue rectangles.

Press 'q' to exit the program.

It prints "guns detected" if a gun is found.



Project Structure
📂 Gun-Detection
 ┣ 📄 gun-detection.py    # Main Python script
 ┣ 📄 cascade.xml         # Haar cascade XML file for gun detection


---

Common Issues & Fixes

1. No module named 'imutils'

pip install imutils


2. Cascade file not found

Ensure cascade.xml is in the correct directory.

Try using the full path in the script:

gun_cascade = cv2.CascadeClassifier(r"C:\Users\LENOVO\Downloads\cascade.xml")


---

Contributing

Feel free to contribute by forking the repo and submitting pull requests.
