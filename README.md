# Face-Detector

A lightweight face detection toolkit built in Python using OpenCV's Haar Cascade classifier. Detects faces in static images and from a live webcam feed.

## Features

- Detect faces in any input image
- Real-time face detection through the system webcam
- Bounding-box overlay on detected faces
- Single-file scripts, no training required (pre-trained Haar Cascade model)

## Tech Stack

- **Language:** Python 3
- **Library:** OpenCV (`cv2`)
- **Model:** Haar Cascade Frontal Face (`haarcascade_frontalface_default.xml`)

## Project Structure

```
Face-Detector/
├── face_detection_in_images.py     # Detect faces in static images
├── face_detector_using camera.py   # Detect faces from live webcam
├── haarcascade_frontalface_default.xml  # Pre-trained Haar Cascade model
└── Image/                          # Sample input images
```

## Setup

```bash
git clone https://github.com/WorkRabdeepSinghKharbanda/Face-Detector.git
cd Face-Detector
pip install opencv-python
```

## Usage

**Detect from image:**
```bash
python face_detection_in_images.py
```

**Detect from webcam:**
```bash
python "face_detector_using camera.py"
```
Press `q` to exit webcam mode.

## License

MIT
