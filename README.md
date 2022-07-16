# Virtual-Mouse using OpenCV
A Python-based project that enabled finger movement to control the mouse cursor in air.

## Project Description:
In this project, my hand serves as a virtual mouse that can perform all mouse-like functions without ever touching your computer. My computer's webcam is being used to find my hands. After that, it will draw 21 landmarks around my hand and concentrate on my index finger and thumb. The index finger will serve as the cursor, and by moving it, we may move the pointer. Currently, it is identifying the distance between the thumb and the index finger in order to correctly click using hand tracking. When they are coupled, there will be a click .

## Requirements:
Following modules need to be installed for it to work properly:
- OpenCV
- Mediapipe
- Pyautogui

### OpenCV:
OpenCV is a huge open-source library for computer vision, machine learning, and image processing. OpenCV supports a wide variety of programming languages like Python, C++, Java, etc. It can process images and videos to identify objects, faces, or even the handwriting of a human.

It can be installed using
```
pip install opencv-python
```

### Mediapipe:
MediaPipe is a framework for building multimodal (eg. video, audio, any time series data), cross platform (i.e Android, iOS, web, edge devices) applied ML pipelines.

It can be installed using 
```
pip install mediapipe
```

If you are facing dependency issues with the above command, you can lower down the version of mediapipe while installing it using 

```
pip install mediapipe==('version')
```

### Pyautogui:
PyAutoGUI lets your Python scripts control the mouse and keyboard to automate interactions with other applications. The API is designed to be simple. PyAutoGUI works on Windows, macOS, and Linux, and runs on Python 2 and 3.

It can be installed using
```
pip install pyautogui
```
