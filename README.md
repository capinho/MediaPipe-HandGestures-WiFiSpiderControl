# MediaPipe Hand Gestures for WiFi Spider Control

This project integrates MediaPipe hand gesture recognition with Arduino, Raspberry Pi, and a Wi-Fi module to control a spider robot. The system interprets hand gestures captured via a webcam, processes them using MediaPipe, and sends corresponding commands to the robot over Wi-Fi for real-time interaction.

## Features

- Real-time hand gesture recognition using MediaPipe.
- Control of a Wi-Fi-enabled spider robot via hand gestures.
- Integration with Arduino and Raspberry Pi for hardware control.
- Customizable TensorFlow Lite models for hand gesture recognition.
- Direct control API for seamless robot manipulation.

## Requirements

- MediaPipe
- OpenCV
- TensorFlow
- Arduino IDE
- Raspberry Pi OS
- Additional libraries as listed in `requirements.txt`

## Installation

Clone the repository:

```bash
git clone https://github.com/capihno/MediaPipe-HandGestures-WiFiSpiderControl.git
cd MediaPipe-HandGestures-WiFiSpiderControl
pip install -r requirements.txt
