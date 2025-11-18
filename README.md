Object Recognition

This project performs real-time blue color detection using a webcam.
It uses HSV color space, color masking, and bitwise operations to highlight blue regions in the video.

   Features

Detects blue objects in real time

Shows original and masked video output

Works with any webcam

Automatically closes when Q is pressed or window close (X) button is clicked

  Requirements

Install dependencies using:

pip install -r requirements.txt

  How to Run

Run the script:

python blue_detection.py

  HSV Range Used for BLUE Color
lower_blue = np.array([94, 80, 2])
upper_blue = np.array([126, 255, 255])

  How It Works

Capture video from webcam

Convert each frame from BGR → HSV

Create a mask for blue color

Apply mask to highlight only blue regions

Display two windows:

Original frame

Blue-detected output

Close window on Q or X

  Exit / Close Instructions

Press Q → Program terminates

Click X on any window → Program terminates
