# YOLOv5 for Object Detection

A PyTorch implementation of **YOLOv5** for real-time object detection. The project supports training, validation, and inference on custom datasets or public benchmarks.

---

## Demo
<p align="center">
  <img src="runs/detect/exp/demo.gif" width="800">

</p>

<p align="center">
Real-time object detection using YOLOv5.
</p>

---

## Requirements

* Python 3.10+
* PyTorch
* TorchVision
* OpenCV
* NumPy
* Matplotlib
* tqdm

```bash
pip install -r requirements.txt
```

---

## Dataset

```text
dataset/
├── images/
│   ├── train/
│   └── val/
├── labels/
│   ├── train/
│   └── val/
└── data.yaml
```

---

## Training

```bash
python train.py
```

---

## Inference

```bash
python detect.py --weights runs/train/exp/weights/best.pt --source demo/test1.jpg
```
"# Yolo-v5-for-object-detection" 
