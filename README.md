# 🤖 AI Robot Vision System

An AI-powered robot vision system built with **YOLOv8**, **Python**, and **OpenCV** for real-time object detection, object counting, JSON export, and robot vision reporting.

---

## 📌 Features

- Detects 80+ COCO object classes
- Draws bounding boxes
- Displays confidence scores
- Counts detected objects
- Exports results to JSON
- Generates a robot vision report
- Works completely in Google Colab

---

## 🛠 Technologies Used

- Python
- YOLOv8
- OpenCV
- NumPy
- Matplotlib
- JSON
- Google Colab
- Git
- GitHub

---

## 📂 Project Structure

```
robot-vision-system/
│
├── notebook/
│   └── Robot_Vision_System.ipynb
│
├── outputs/
│   ├── detections.json
│   └── detected_kitchen.png
│
├── screenshots/
│   ├── detection_result.png
│   └── robot_report.png
│
├── sample_images/
│   └── green-farmhouse-kitchen.avif
│
├── README.md
└── LICENSE
```

---

## 📸 Screenshots

### Object Detection

![Detection](screenshots/detection_result.png)

---

### Robot Vision Report

![Report](screenshots/robot_report.png)

---

## 📊 Sample JSON Output

```json
[
  {
    "object": "bowl",
    "confidence": 0.86,
    "bounding_box": {
      "x1": 503.97,
      "y1": 565.72,
      "x2": 572.77,
      "y2": 615.29
    }
  }
]
```

---

## 🚀 How to Run

1. Open Google Colab.
2. Install required libraries.
3. Load the YOLOv8 model.
4. Upload an image.
5. Run object detection.
6. View results.
7. Export detections to JSON.

---

## 📈 Future Improvements

- Real-time webcam detection
- Video object detection
- Multi-object tracking
- ROS2 integration
- Mobile robot navigation

---

## 👩‍💻 Author

**Harsha**

AI | Robotics | Computer Vision | Python