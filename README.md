# Number Detection using YOLO
This project implements a number detection system using YOLO (You Only Look Once) object detection algorithm. The system is trained on Pascal VOC XML formatted data.

## Author
KhanhRomVN


## Setup

1. Clone the repository:
   ```
   git clone https://github.com/KhanhRomVN/number-detection-yolo.git
   cd number-detection-yolo
   ```

2. Create a virtual environment (optional but recommended):
   ```
   python -m venv venv
   source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
   ```

3. Install the required packages:
   ```
   pip install -r requirements.txt
   ```

## Data Preparation

The dataset should be in Pascal VOC XML format, organized into three directories:
- `data/train/`: Training data
- `data/valid/`: Validation data
- `data/test/`: Test data

Each directory should contain image files and corresponding XML annotation files.

## Training

To train the model, run:
```
python train.py
```

