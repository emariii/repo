# README
## Hand Gesture Recognition for Controlling Computer's Mouse Cursor
This is a Python project for controlling a computer's mouse cursor using hand gestures. The program recognizes hand gestures through a webcam using the Mediapipe library and controls the mouse cursor via the PyAutoGUI library.

The project is divided into two files, `app.py` and `controller.py`. The `app.py` file contains the main program logic while `controller.py` is responsible for handling the mouse cursor movement and click events.

There is an extra file, `requirements.txt` which you can use to install the libraries required for this project.

## Requirements
#### To run the program, the following libraries are required:<br>
  - OpenCV<br>
  - Mediapipe<br>
  - PyAutoGUI<br>
 
#### You can install these libraries using pip:<br>
  -  `pip install opencv-python mediapipe pyautogui`<br>
#### Or you can use the following command using pip to avoid any library version issue:<br>
  - `pip install -r requirements.txt`

# How to Run
After installing the required libraries, run the `app.py` file in a Python environment with a webcam. The program will start capturing video from the webcam, and the mouse cursor can be controlled using the following hand gestures:

  - **Drag and drop**: Close your hand into a fist and move it around to drag and drop objects.
  - **Right-click**: Raise your index finger while keeping the other fingers closed.
  - **Left-click**: Raise your middle finger while keeping the other fingers closed.
  - **Double-click**: Raise your index and middle finger while keeping the other fingers closed.
  - **Scroll up**: Move your index and middle finger towards the screen.
  - **Scroll down**: Move your index and middle finger away from the screen.
  - **Zoom in**: Pinch your index finger and thumb together.
  - **Zoom out**: Spread your index finger and thumb apart.

# Demo
The repository includes some demo GIFs to help you understand how to use hand gestures to control the mouse. The GIFs show the different hand gestures and their corresponding mouse actions in action, making it easy to follow along and learn how to use the program. To view the demo GIFs, simply navigate to the `demo/` folder in the repository and open the GIFs using any image viewer.<br>

We hope these demos make it easier for you to get started with the program and learn how to use it effectively. If you have any questions or feedback, feel free to reach out to us!

# How it Works
The program uses the Mediapipe library to detect hand landmarks from the video captured by the webcam. The `controller.py` file contains the logic for mapping the hand landmarks to specific mouse cursor actions, such as movement and clicking.

# Limitations
The program currently only supports controlling a single mouse cursor, and it may not work well in low-light conditions.

# License
This project is licensed under the MIT License. Feel free to use, modify and distribute the code as you see fit.
