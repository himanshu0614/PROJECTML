# Drowsiness Detection System

## Overview
This project is a real-time drowsiness detection system that uses OpenCV and Haar cascades to detect faces and eyes. It continuously monitors eye activity and alerts when drowsiness is detected.

## Features
- Real-time face and eye detection
- Blink rate calculation
- Drowsiness alert based on eye closure duration
- Displays eye closure duration and blink rate
- Visual alerts for drowsiness detection

## Requirements
Ensure you have the following dependencies installed before running the script:

```bash
pip install opencv-python numpy
```

## How to Run
Run the following command to start the drowsiness detection system:

```bash
python drowsiness.py
```

## How It Works
1. Captures live video feed using OpenCV.
2. Detects face and eyes using Haar cascade classifiers.
3. Monitors eye closure duration:
   - If eyes are closed for more than a threshold time (1.5s), it triggers a drowsiness alert.
   - If eyes are open, the system remains in "Active" mode.
4. Tracks blink rate (blinks per minute) to analyze user fatigue.
5. Displays real-time status, blink rate, and eye closure duration on the screen.

## Controls
- Press `q` to exit the application.

## Future Enhancements
- Integrate audio alerts for drowsiness detection.
- Improve accuracy using deep learning models.
- Deploy on mobile or embedded systems for real-world applications.

## License
This project is open-source and free to use under the MIT License.

## Author
Himanshu Singh

