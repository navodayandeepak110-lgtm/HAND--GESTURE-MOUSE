# Hand Gesture Control System V1

A software-only solution to control your PC mouse using hand gestures via a webcam. Built with Python, OpenCV, and MediaPipe.

## Features (Version 2)
-   **Multi-Mode Interaction**:
    -   **MOVE MODE**: Standard cursor control.
    -   **SCROLL MODE**: Intuitive hand-movement scrolling.
    -   **PAUSED MODE**: Safety state.
-   **Expanded Gestures**:
    -   **Right Click**: Thumb + Middle Pinch.
    -   **Left Click**: Thumb + Index Pinch.
-   **Advanced Safety**:
    -   **Global Kill Switch ('Q')**.
    -   **Auto-Pause**: Activates on hand loss or low FPS.
    -   **Cooldowns**: Prevents accidental double-clicks.
-   **Visual Dashboard**:
    -   Real-time Mode, FPS, and Gesture display.

## Prerequisites
-   Python 3.8+
-   Webcam
-   MediaPipe Model (`hand_landmarker.task`)

## Setup Instructions

1.  **Clone/Download** this repository.
2.  **Install Dependencies**:
    ```bash
    pip install -r requirements.txt
    ```
3.  **Download Model**:
    The system requires the `hand_landmarker.task` model file. [Download Link](https://storage.googleapis.com/mediapipe-models/hand_landmarker/hand_landmarker/float16/1/hand_landmarker.task) or use:

