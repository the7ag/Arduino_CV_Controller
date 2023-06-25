# Arduino Computer Vision Controller

![Screenshot_1](https://github.com/the7ag/Arduino_CV_Controller/assets/95578914/ea1807de-ada8-4bad-9771-dde20b7a9774)

## Overview

The Arduino Computer Vision Controller is a project that aims to provide a simple and intuitive way to control an Arduino board using computer vision techniques. By leveraging the power of computer vision, this project allows you to interact with your Arduino-based projects without the need for physical buttons or switches.

The controller utilizes a webcam or a compatible camera module to capture real-time video input. It then processes the video frames using computer vision algorithms to detect specific gestures or objects. These detected gestures or objects are mapped to corresponding actions on the Arduino board, enabling you to control various components and functions of your Arduino projects.

## Features

- Real-time video input from a webcam or camera module.
- Computer vision algorithms for gesture and object detection.
- Mapping of detected gestures or objects to Arduino actions.
- Easy integration with Arduino projects.
- Configurable thresholds and parameters for gesture/object detection.
- Support for multiple platforms (Windows, macOS, Linux).

## Video


https://github.com/the7ag/Arduino_CV_Controller/assets/95578914/f624ddb2-c06d-4db0-94a8-ee9ccacc368c


## Installation

1. Clone the repository to your local machine:

```bash
git clone https://github.com/the7ag/Arduino_CV_Controller.git
```

2. Install the required dependencies:

```bash
pip install -r requirements.txt
```

3. Connect your Arduino board to your computer via USB.

4. Upload the Arduino sketch located in the `arduino` directory to your Arduino board using the Arduino IDE.

## Usage

1. Connect a webcam or camera module to your computer.

2. Run the main script:

```bash
python main.py
```

3. The main script will launch and display the video feed from the camera.

4. Perform the desired gestures or present the specified objects to control the Arduino board.

5. The corresponding actions will be executed on the Arduino board based on the detected gestures or objects.

## Configuration

The configuration file `config.json` allows you to customize various parameters of the Arduino Computer Vision Controller. You can modify the following settings:

- `video_source`: Specify the video source index (default: `0` for the default camera).
- `gesture_thresholds`: Set the threshold values for gesture detection.
- `object_mapping`: Map detected objects to specific Arduino actions.

## Contributing

Contributions to the Arduino Computer Vision Controller project are always welcome! If you want to contribute, follow these steps:

1. Fork the repository.

2. Create a new branch:

```bash
git checkout -b feature/your-feature
```

3. Make your changes and commit them:

```bash
git commit -m "Add your feature"
```

4. Push to the branch:

```bash
git push origin feature/your-feature
```

5. Open a pull request.

## License

This project is licensed under the [MIT License](LICENSE).

## Acknowledgements

- The [OpenCV](https://opencv.org/) library for computer vision algorithms.
- The [pySerial](https://github.com/pyserial/pyserial) library for serial communication with Arduino.
- The [pyFirmata](https://pypi.org/project/pyFirmata/) library for communication with Arduino
- The Arduino community for their valuable resources and support.

## Contact

If you have any questions, suggestions, or issues regarding the Arduino Computer Vision Controller, feel free to contact the project maintainer:

mohamed Ali
[Email](the7ag22477@gmail.com)
[Linked In](https://www.linkedin.com/in/mohamedali123/)

I appreciate your interest in the project!
