This project is a touchless Human–Computer Interaction system that allows controlling applications using hand gestures in the air without touching the screen. The system uses a camera and AI-based hand tracking (MediaPipe) to detect finger movements and convert them into real actions such as mouse movement, clicking, scrolling, and window control.

It can be used to control:

PDF page scrolling

Instagram scrolling

Photo sliding

Web browsing

Any desktop application

This is the base system that will later be extended to Android for full phone control.

2. Technologies Used

Python

OpenCV

MediaPipe Hands

PyAutoGUI

Computer Vision

Artificial Intelligence

Human Computer Interaction (HCI)

3. Features

Real-time hand tracking using webcam

Cursor control using index finger

Left click using Index + Middle finger

Right click using Thumb + Index finger

Double click using Thumb + Index + Middle finger

Scroll up/down using hand position

Close active window using fist gesture

ON/OFF toggle using keyboard key K

Exit using ESC key

One-click start using BAT file

4. Gesture Mapping
Gesture	Action
Index finger move	Move mouse cursor
Index + Middle	Left click
Thumb + Index	Right click
Thumb + Index + Middle	Double click
Hand up	Scroll up
Hand down	Scroll down
Fist	Close current window (Alt + F4)
Press K	Toggle system ON / OFF
Press ESC	Exit program
5. Project Files
AirGestureControl/
│
├── hand_control.py        -> Main gesture recognition code
├── requirements.txt      -> Python dependencies
├── StartHandControl.bat  -> One-click start file
├── README.md             -> Documentation

6. Installation Steps
Step 1: Install Python

Download Python 3.9 or above from:
https://www.python.org

(Check “Add Python to PATH” during installation)

Step 2: Install Required Libraries

Open Command Prompt inside the project folder and run:

pip install -r requirements.txt


Contents of requirements.txt:

opencv-python
mediapipe
pyautogui

7. How to Run
Method 1: Using Start BAT (Recommended)

Double-click:

StartHandControl.bat


Contents of StartHandControl.bat:

python hand_control.py

Method 2: Using Command Line
python hand_control.py

8. ON / OFF Toggle System

The system can be paused and resumed without closing:

Press K → Gesture Control ON

Press K again → Gesture Control OFF

Camera continues running but actions stop when OFF

This allows safe usage and demonstration control.

9. Future Android Implementation

This project will be extended to Android using:

Phone Camera

MediaPipe Hands

Android Accessibility Services

So that:

Instagram can be scrolled by air

PDFs can be turned by air

Photos can be slid by air

Apps can be controlled without touching the screen

10. Author

Krishna Sanjay Pemmaraju
Project Domain:
Artificial Intelligence, Computer Vision, Human Computer Interaction

Project Title:
Air Gesture Based Touchless Application Control System

11. Conclusion

This project demonstrates a real-time air-gesture interface that allows users to interact with digital systems using natural hand movements, enabling touchless control and forming a foundation for future AR/VR, smart display, and mobile gesture-based interfaces.
