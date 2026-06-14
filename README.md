# 🚀 Object Detection and Tracking using YOLOv8

## 📌 Overview

This project is a real-time Object Detection and Multi-Object Tracking system developed as part of the CodeAlpha Artificial Intelligence Internship.

The system uses YOLOv8 for object detection and ByteTrack for object tracking. It can identify multiple objects in a video stream, draw bounding boxes around them, and assign unique tracking IDs to each detected object.

---

## 🎯 Features

* Real-time Object Detection
* Multi-Object Tracking
* Unique Tracking IDs
* Webcam Support
* Video File Support
* High-Speed Processing
* Automatic Object Labeling
* Bounding Box Visualization

---

## 🛠️ Technologies Used

* Python
* OpenCV
* YOLOv8 (Ultralytics)
* ByteTrack
* NumPy

---

## 📂 Project Structure

ObjectDetectionTracking/

├── main.py

├── requirements.txt

├── output.mp4

├── screenshots/

│ ├── screenshot1.png

│ └── screenshot2.png

└── README.md

---


### Install Dependencies

pip install -r requirements.txt

---

## ▶️ Run the Project

python main.py

The webcam will start automatically and begin detecting and tracking objects in real time.

---

## 📹 Using a Video File

Replace:

cap = cv2.VideoCapture(0)

With:

cap = cv2.VideoCapture("video.mp4")

Place your video file in the project folder and run the script again.

---

## 📊 Output

The system displays:

* Object Labels
* Bounding Boxes
* Tracking IDs
* Real-Time Detection Results

Example:

Person ID: 1

Person ID: 2

Car ID: 3

Bus ID: 4

---

## 💡 Applications

* Smart Surveillance Systems
* Traffic Monitoring
* Security and Safety
* Smart Cities
* Autonomous Vehicles
* Crowd Analysis


## 🤝 Acknowledgements

Special thanks to CodeAlpha for providing the opportunity to work on real-world Artificial Intelligence projects and enhance practical skills in Computer Vision.

---

## 👨‍💻 Author

Ali Abdur Rehman

CodeAlpha Artificial Intelligence Intern
---

⭐ If you found this project useful, please give it a star!
