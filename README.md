Eye-Controlled Mouse using OpenCV, MediaPipe, and PyAutoGUI
This project utilizes computer vision techniques with OpenCV and MediaPipe to track facial landmarks, particularly focusing on eye movements. PyAutoGUI is then used to control the mouse cursor based on the detected eye movements. This enables users to control the mouse solely through their eye movements, offering an alternative input method.

Requirements
Python 3.x
OpenCV (pip install opencv-python)
MediaPipe (pip install mediapipe)
PyAutoGUI (pip install pyautogui)
Usage
Clone this repository to your local machine:
bash
Copy code
git clone https://github.com/yourusername/eye-controlled-mouse.git
Navigate into the cloned directory:
bash
Copy code
cd eye-controlled-mouse
Run the Python script:
bash
Copy code
python eye_controlled_mouse.py
Position your face in front of the camera, and move your eyes to control the mouse cursor. Blinking may trigger a mouse click.
Customization
You can adjust the sensitivity of the mouse movement and clicking thresholds by modifying the code.
Experiment with different facial landmarks or gestures for additional functionalities.
Acknowledgements
This project is based on the following technologies:

OpenCV: https://opencv.org/
MediaPipe: https://mediapipe.dev/
PyAutoGUI: https://pyautogui.readthedocs.io/en/latest/
License
This project is licensed under the MIT License.
