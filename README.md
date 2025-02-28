# FaceMesh

A real-time face mesh detection using OpenCV and MediaPipe libraries. Video is captured from a webcam, facial landmarks are detected and displayed on a black background. 🕵️‍♂️


![CleanShot 2024-10-01 at 01 18 46@2x](https://github.com/user-attachments/assets/6e8622e4-3f13-4671-9e5d-181db5c9dbab)

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
