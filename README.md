```markdown
# Eye-Controlled Mouse using OpenCV, MediaPipe, and PyAutoGUI

This project utilizes computer vision techniques with OpenCV and MediaPipe to track facial landmarks, particularly focusing on eye movements. PyAutoGUI is then used to control the mouse cursor based on the detected eye movements. This enables users to control the mouse solely through their eye movements, offering an alternative input method.

## Requirements

- Python 3.x
- OpenCV (`pip install opencv-python`)
- MediaPipe (`pip install mediapipe`)
- PyAutoGUI (`pip install pyautogui`)

## Usage

1. Clone this repository to your local machine:

```bash
git clone https://github.com/Plasma-69/move_mouse_withface.git
```

2. Navigate into the cloned directory:

```bash
cd move_mouse_withface
```

3. Run the Python script:

```bash
python move_mouse_withface.py
```

4. Position your face in front of the camera, and move your eyes to control the mouse cursor. Blinking may trigger a mouse click.

## Customization

- You can adjust the sensitivity of the mouse movement and clicking thresholds by modifying the code.
- Experiment with different facial landmarks or gestures for additional functionalities.

## Acknowledgements

This project is based on the following technologies:

- OpenCV: [https://opencv.org/](https://opencv.org/)
- MediaPipe: [https://mediapipe.dev/](https://mediapipe.dev/)
- PyAutoGUI: [https://pyautogui.readthedocs.io/en/latest/](https://pyautogui.readthedocs.io/en/latest/)

## License

This project is licensed under the MIT License.
```
