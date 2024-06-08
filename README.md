# Human Motion Capture and Transfer to Unity

This project leverages computer vision techniques to capture human motion from video and transfer it to a 3D character in Unity. The system uses MediaPipe for real-time body landmark detection and maps the detected motion data to animate a character rig in Unity.

## DEMO VIDEO:
Video 1: https://drive.google.com/file/d/12v8SinpwfkfsJHsPan810_8YDsF4_M3d/view?usp=sharing

Video 2: https://drive.google.com/file/d/1c_iJ1rDHZwN2nzNupEyhyPyNUBgD8_tu/view?usp=sharing

## Features

- **Real-Time Motion Capture**: Utilizes MediaPipe's BlazePose model to detect and track 33 body landmarks from video frames.
- **Unity Integration**: Seamlessly transfers the captured motion data to Unity, animating a predefined 3D character rig.
- **Cross-Platform**: Supports motion capture from various video sources, including webcams and pre-recorded videos.

## Getting Started

### Prerequisites

- Python 3.x
- Unity (version X.X.X or later)
- OpenCV (`pip install opencv-python`)
- MediaPipe (`pip install mediapipe`)
- NumPy (`pip install numpy`)


### Contributing
Contributions are welcome! If you have any ideas, suggestions, or improvements, please open an issue or submit a pull request.

### License
This project is licensed under the MIT License.

### Acknowledgments
MediaPipe - Google's open-source machine learning solution for perception
Unity - Cross-platform game engine
