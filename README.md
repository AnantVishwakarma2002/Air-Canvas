# AI-powered Air Canvas

*******************************WELCOME TO AI AIR CANVAS*******************************

An innovative application that allows users to create digital drawings by translating their finger movements into graphical representations using real-time computer vision.

## Requirements

1. **WebCam**: At least 720p at 60fps for optimal performance.
2. **Python**: Ensure Python is installed on your system.

## Installing Dependencies

To install the required Python libraries for the successful execution of the code, run the following commands in the command prompt:

```bash
pip install opencv-python
pip install numpy
pip install time
pip install mediapipe
```

## Running the Application

Once the libraries are installed, you can run the main application:

```bash
python air_canvas.py
```

## Dataset and Modules

For hand tracking, finger tip position, and detecting which fingers are up, we have created a Track_hands_module.py file. This module is imported as Track_hands_Module in the Air_canvas.py file. The Track_hands_module utilizes the mediapipe library at the backend, which provides various methods to detect objects in video feeds or images
