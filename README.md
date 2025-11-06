# PPE Detection using Yolo

## Breif Description
AI-based real-time PPE detection system for construction sites using YOLO object detection models. The system is trained to identify hardhats, vests, gloves, goggles, and boots. A Python/OpenCV pipeline enables offline detection, validated on 200 manually annotated images.

## Fetching the Files from the Repo
```bash
git clone https://github.com/nishchithakrishna/yolodetect.git
```
```bash
cd yolodetect
```


## Execution Environment Setup
1. Create a virtual environment
```bash
python3 -m venv venv
```

2. Activate the virtual environment
```bash
source venv/bin/activate    # macOS/Linux
```

```bash
venv\Scripts\activate      # Windows
```

3. Install project dependencies
```bash
pip install --upgrade pip
```
```bash
pip install -r requirements.txt
```

## Excecuting the Program
```bash
python GH_yolo_detect.py --model my_model.pt --source 0 --resolution 1280x720       # macOS/Linux
```
```bash
python GH_yolo_detect.py --model my_model.pt --source usb0 --resolution 1280x720       # Windows
```

