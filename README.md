# 🚗 Car Counting Using YOLOv8

This project detects, tracks, and counts cars in a highway video using
YOLOv8, ByteTrack, and Supervision.

## 🔍 Features
- Car detection using YOLOv8
- Object tracking using ByteTrack
- Line-based car counting
- Output video with bounding boxes and counts

## 🛠 Technologies Used
- Python
- YOLOv8 (Ultralytics)
- Supervision
- OpenCV
- Google Colab

## ▶ How It Works
1. YOLO detects cars in each video frame
2. ByteTrack assigns a unique ID to each car
3. A virtual line is placed on the road
4. When a car crosses the line, it is counted
5. The result is saved as a new video

## 📂 Files
- `Counting_car_yolo.ipynb` – Main Colab notebook
- `Before_counting.mp4` – Input video
- `Output(after_counting).mp4` – Output video with counting

## 🚀 How to Run
Open the notebook in Google Colab and run all cells.

## 📌 Author
Muhammad Haris
