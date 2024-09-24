Air Canva

Welcome to Air Canva, a hand gesture painting application that lets you create art using hand movements detected through your webcam. This project combines the power of OpenCV for computer vision and MediaPipe for real-time hand tracking.


Features

Interactive Painting: Draw with different colors using your fingers.

Color Selection: Easily switch between colors (Blue, Green, Red, Yellow) with hand gestures.

Clear Canvas: Reset the canvas with a simple gesture.

Real-Time Feedback: See your artwork come to life instantly!


Requirements


To run this application, you need to have Python installed along with the following libraries:

OpenCV

NumPy

MediaPipe


You can install the required libraries using pip:


pip install opencv-python numpy mediapipe


Installation


Clone this repository to your local machine:


git clone https://github.com/Princekumar7999/air_canva.git


cd air_canva

Ensure your webcam is connected and functioning properly.

Run the application with the following command:

python hand_painting.py

A window will open displaying your webcam feed.


Use your index finger to draw on the canvas. Here's how to interact:


Draw: Point your finger at the canvas area.

Select Color: Point your finger at the color buttons located at the top of the window.

Clear Canvas: Point your finger at the "CLEAR" button to reset the canvas.

Press 'q' to exit the application.

How It Works
The application initializes a webcam feed and utilizes MediaPipe to detect hand landmarks.
Depending on the position of the index finger and thumb, it determines whether to draw on the canvas or switch colors.
The drawn points are stored in deque data structures for efficient drawing.
