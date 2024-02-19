# Hand Gesture Controlled Presentation using MediaPipe

This project enables users to control presentations using hand gestures captured through the MediaPipe library.

## Overview

The Hand Gesture Controlled Presentation system allows users to navigate through presentation slides using predefined hand gestures. It utilizes the MediaPipe library to detect hand landmarks and interpret gestures in real-time.

## Features

- Real-time hand gesture recognition for presentation control.
- Support for common presentation actions such as next slide, previous slide, start presentation, and end presentation.
- User-friendly interface with intuitive gesture mappings.

## Requirements

To run the project, ensure you have the following dependencies installed:

- Python 3.x
- MediaPipe library
- OpenCV
- PyAutoGUI
- NumPy

You can install the dependencies using pip:

```bash
pip install mediapipe opencv-python pyautogui numpy
```

## Usage

1. Clone the repository to your local machine.
2. Run the `hand_gesture_presentation.py` script.
3. Ensure that your webcam is enabled and positioned properly to capture hand gestures.
4. Follow the on-screen instructions to control the presentation using hand gestures.

## Supported Gestures

The system currently supports the following hand gestures:

- **Fist**: Start or end presentation mode.
- **Index finger extended**: Move to the next slide.
- **Thumb extended**: Move to the previous slide.

## Contributing

Contributions to the project are welcome! If you have any suggestions, feature requests, or bug reports, please open an issue or submit a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgments

- Special thanks to the MediaPipe team for providing the hand tracking and gesture recognition functionality.
- Thanks to the OpenCV and PyAutoGUI communities for their valuable contributions.

## Author

Aparna

Feel free to customize the content and structure of the README file to suit your project's specific details and requirements.
