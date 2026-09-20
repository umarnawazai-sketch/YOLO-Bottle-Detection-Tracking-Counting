# YOLO Bottle Detection, Tracking, and Counting

Real-time bottle detection and multi-object tracking implemented using YOLOv8 and OpenCV in Python.

## Features
- **Object Detection & Tracking:** Leverages YOLOv8 for detecting and tracking objects across video frames.
- **Class Filtering:** Configured to target specific class IDs (e.g., COCO class ID `39` for bottles).
- **Video & Stream Support:** Processes both local `.mp4` video files and live webcam input.

## Prerequisites
Ensure Python 3.8+ is installed on your system.

## Setup Instructions

1. **Clone the Repository:**
   ```bash
   git clone [https://github.com/umarnawazai-sketch/YOLO-Bottle-Detection-Tracking-Counting.git](https://github.com/umarnawazai-sketch/YOLO-Bottle-Detection-Tracking-Counting.git)
   cd YOLO-Bottle-Detection-Tracking-Counting
Set Up Virtual Environment:

Bash
python -m venv .venv
source .venv/Scripts/activate
Install Dependencies:

Bash
pip install ultralytics opencv-python numpy
Usage
Run the main tracking script:

Bash
python bottle_tracking.py
Note: To switch between local video and live webcam, edit line 7 in bottle_tracking.py:

Local video: cap = cv2.VideoCapture("bootle_tracking.mp4")

Live webcam: cap = cv2.VideoCapture(0)


---

### What to do next:

1. Open `README.md` in VS Code or Notepad, paste the code above, and **save the file**.
2. Run these commands in your Git Bash terminal to send it to GitHub:

```bash
git add README.md
git commit -m "Complete README documentation"
git push origin main
