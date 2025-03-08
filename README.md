# YOLOv11: Exploring the Next Evolution of Object Detection

## 📌 Project Overview

This repository is dedicated to experimenting with **YOLOv11**, an advanced version of the YOLO object detection model. The primary objective is to compare **YOLOv11** against previous versions regarding accuracy, speed, and efficiency across various datasets and benchmarks.

## ⚙️ Installation

To set up this project and experiment with **YOLOv11**, follow these steps:

```bash
# Clone the repository
git clone https://github.com/melanieyes/yolov11.git
cd yolov11

# Create a virtual environment (optional but recommended)
python -m venv yolov11_env
source yolov11_env/bin/activate  # On Windows use: yolov11_env\Scripts\activate

# Install dependencies
pip install -r requirements.txt
```

## 🚀 Running YOLOv11

### Running YOLOv11 (Experimental Model)

```bash
# Run inference using YOLOv11
python detect.py --source data/sample.jpg --weights yolov11.pt --conf 0.25
```

### Running YOLOv3 to YOLOv8 (Baseline Models for Comparison)

```bash
# Example for YOLOv5
git clone https://github.com/ultralytics/yolov5.git
cd yolov5
pip install -r requirements.txt
python detect.py --source data/sample.jpg --weights yolov5s.pt --conf 0.25
```

## 📊 Evaluation Metrics

Each model is evaluated based on the following key metrics:

- **mAP (Mean Average Precision)**
- **FPS (Frames Per Second) - Inference Speed**
- **Model Size (MB)**
- **Training Time & Computational Cost**


## 📬 Contact

Feel free to reach out:

- **GitHub Issues**: [Open an issue](https://github.com/melanieyes/yolov11/issues)


