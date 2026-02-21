# Machine Vision Bottle Detection System

This project detects bottles using a camera or video. It uses computer vision techniques to find and highlight bottles in real-time.

## Features
- Detect bottles in images or live video
- Highlights detected bottles with bounding boxes
- Works for different bottle sizes

## Requirements
- Python 3.x
- OpenCV
- NumPy

## How to Use
### Detect Bottles in an Image
python detect_image.py --image path_to_image.jpg

### Detect Bottles in Video / Camera
python detect_video.py --source 0
(Note: --source 0 uses your webcam. You can change it to a video file path.)

## How It Works
1. Capture image or video frame
2. Process the frame (grayscale, blur, edges)
3. Detect bottles using contours or ML model
4. Draw boxes around bottles
5. Display results

## Author
Naveen Kumar S
GitHub:https://github.com/Naveen-kumar08
