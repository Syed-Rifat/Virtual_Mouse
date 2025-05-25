# Live Mouse Control Using Hand Gestures

This project allows you to control your computer mouse using hand gestures captured through your webcam. It uses computer vision and machine learning to track hand movements and translate them into mouse actions.

## Features

- Real-time hand tracking
- Mouse movement control
- Left click gesture
- Right click gesture
- Double click gesture
- Screenshot capture gesture

## Requirements

- Python 3.10 or later
- Webcam
- Required Python packages (see requirements.txt)

## Installation

1. Clone this repository:
```bash
git clone [your-repository-url]
cd live_mouse_control_using_hand_gestures
```

2. Install the required packages:
```bash
pip install -r requirements.txt
```

## Usage

Run the main script:
```bash
python main.py
```

### Gesture Controls

- Move your index finger to control mouse movement
- Pinch thumb and index finger for left click
- Pinch thumb and middle finger for right click
- Pinch thumb, index, and middle fingers for double click
- Pinch thumb and index finger close together for screenshot

Press 'q' to quit the application.

## Dependencies

- OpenCV (cv2)
- MediaPipe
- PyAutoGUI
- pynput

## License

[Your chosen license] 