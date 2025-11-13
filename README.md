# Football Player Tracking & Team Identification Pipeline

An end-to-end football video analysis system for detecting, tracking, and assigning team colors to players, referees, and the ball. The pipeline processes videos and outputs annotated videos with custom visualizations.

## Features

- **Player, referee, and ball detection** using YOLOv11.
- **Multi-object tracking** with ByteTrack.
- **Team identification** via color-based re-identification (HSV histograms and hue vectors).
- **Custom visualizations**: ellipses for players, triangles for the ball, and team labels.
- **Automated annotated video generation**.

## Technologies & Tools

- Python
- OpenCV
- Ultralytics YOLO
- Roboflow
- NumPy
- scikit-learn
- Supervision
- EasyOCR
- Matplotlib

## Installation

1. Clone the repository:
```bash
git clone https://github.com/ELHALOSE/Football-Player-Tracking.git
cd Football-Player-Tracking
```

2. install the main dependencies directly:
```bash
pip install ultralytics roboflow deep_sort_realtime supervision easyocr scikit-learn tqdm opencv-python matplotlib
```

## Result
[![Annotated Video](screenshot.png)](CV_Task.mkv)

