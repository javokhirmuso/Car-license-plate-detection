# Vehicle License Plate Detection using YOLO11n

This project implements a license plate detection system using YOLO11n model for real-time vehicle license plate detection.

## Dataset

- **Source**: Roboflow Universe
- **Project**: License Plate Recognition
- **Classes**: 1 (License_Plate)
- **License**: CC BY 4.0
- **Version**: 6

## Project Structure
```
├── data
│   ├── train/images
│   ├── valid/images
│   └── test/images
├── models
│   └── yolov8n.pt
├── detect.py
├── train.py
└── data.yaml
```

## Setup

```bash
# Clone repository
git clone <repository-url>
cd <repository-name>

# Install requirements
pip install ultralytics
pip install -r requirements.txt
```




## Results

- ** prediction **
- 
  <img src="results\val_batch0_pred.jpg" height="70%" width="70%"
        style="object-fit:contain"
    />
- **label**
- 
  <img src="results\val_batch0_labels.jpg" height="70%" width="70%"
        style="object-fit:contain"
    />


## Acknowledgments
- Dataset from Roboflow Universe
- YOLO11 by Ultralytics
