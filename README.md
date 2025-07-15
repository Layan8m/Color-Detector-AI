# Color-Detector-AI
This project is a real-time color recognition tool using OpenCV and a webcam. When the user clicks on any point in the video frame, the program detects and displays the basic color name along with the RGB values of the selected pixel.
## Features

- Real-time video feed using webcam
- Detects and classifies basic colors (Red, Green, Blue, Yellow, Magenta, Cyan, Black, White, Gray)
- Displays color name and RGB values on click
- Visual color overlay and text label for user interaction

## How It Works

- The program captures frames from the webcam.
- On mouse click, it reads the color of the clicked pixel.
- A function classifies the pixel into a basic color category.
- The result is displayed as a colored rectangle with the RGB values and name.

##  Requirements

- Python 
- OpenCV 
- NumPy

To install:
pip install opencv-python numpy
