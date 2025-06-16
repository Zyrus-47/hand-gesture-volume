# Hand Gesture Volume Control

This Python project allows users to control system volume using simple hand gestures. By tracking the distance between the index finger and thumb via a webcam, it simulates volume up/down actions using keyboard events.

## Features

- Hand detection using MediaPipe
- Real-time webcam feed processing with OpenCV
- Distance-based volume control using:
  - Index finger tip (Landmark 8)
  - Thumb tip (Landmark 4)
- Automatic volume up/down using `pyautogui`
- Visual feedback with colored circles and lines

## Tech Stack

- Python
- OpenCV
- MediaPipe
- PyAutoGUI

## How It Works

- Open hand (fingers far apart): Increases volume  
- Closed hand (fingers close): Decreases volume

## Screenshot

![Screenshot](https://github.com/Zyrus-47/hand-gesture-volume/blob/main/Screenshot%202025-06-16%20214858.png)

## Setup Instructions

1. Clone the repository:
   ```bash
   git clone https://github.com/Zyrus-47/hand-gesture-volume.git
   cd hand-gesture-volume
