# YOLOv8 First Run

My first object detection experiment using Ultralytics YOLOv8n.

## Environment
- Laptop: HP (Intel i5, 16GB RAM)
- GPU: NVIDIA GTX 1650 Ti (4GB)
- OS: Windows 10/11
- PyTorch: 2.5.1 + CUDA 12.1
- Python: 3.10 (conda env: dl)

## Result
Tested on the official bus.jpg sample:
- 4 persons, 1 bus, 1 stop sign

## How to run
\`\`\`powershell
conda activate dl
yolo predict model=yolov8n.pt source='https://ultralytics.com/images/bus.jpg'
\`\`\`
- Environment verified: PyTorch 2.5.1+cu121, CUDA ✅, GTX 1650 Ti (2026-09-13)