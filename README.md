# FaceMesh

This project implements a real-time face mesh detection using OpenCV and MediaPipe libraries. It captures video from your webcam, detects facial landmarks, and displays them on a black background. 🕵️‍♂️

## Installation

1. Clone this repository
2. Install the required packages:
   ```
   pip install opencv-python mediapipe numpy
   ```

## Features

- Real-time face mesh detection
- Mirror effect for natural interaction
- FPS (Frames Per Second) calculation
- Lower resolution setting for improved performance

## Requirements

- Python 3.x
- OpenCV (`cv2`)
- MediaPipe (`mediapipe`)
- NumPy (`numpy`)

## Usage

Run the script using Python:

```
python facemesh.py
```

Once the script is running:

- Your webcam will activate, and you'll see a black window with your face mesh overlaid.
- Press 'q' to quit the application.
- Press 'r' to toggle between full resolution and lower resolution mode.

## Configuration

You can adjust the following parameters in the `facemesh.py` file:

- `RESOLUTION_FACTOR`: Change this value to adjust the resolution. Lower values will increase performance but decrease image quality.
- `MAX_NUM_FACES`: Set the maximum number of faces to detect simultaneously.

## Troubleshooting

If you encounter any issues:

1. Ensure your webcam is properly connected and not being used by another application.
2. Check that you have installed all required dependencies.
3. Make sure you have sufficient lighting for accurate face detection.
