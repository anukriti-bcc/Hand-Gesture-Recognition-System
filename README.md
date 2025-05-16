# Hand-Gesture-Recognition-System
This project demonstrates a hand gesture-controlled LED system using the ESP32 microcontroller, Python, OpenCV, and MediaPipe. The system enables users to control five LEDs—each corresponding to a finger—through simple hand movements detected via a webcam. By leveraging computer vision, embedded systems, and IoT networking, this project bridges the gap between software-based gesture recognition and real-world hardware control.

The gesture recognition process is handled using Python and MediaPipe, a powerful library designed for hand-tracking and gesture recognition. The detected hand gestures are processed and mapped to specific LED control commands. These commands are then transmitted wirelessly over Wi-Fi to the ESP32 microcontroller, which acts as a server. The ESP32 receives the commands via HTTP requests and controls the LEDs connected to its GPIO pins, turning them on or off based on the detected gestures.

Circuit:
<img src="https://github.com/anukriti-bcc/Hand-Gesture-Recognition-System/blob/main/image.png?raw=true" width="400"/>

Output:
<img src="https://github.com/anukriti-bcc/Hand-Gesture-Recognition-System/blob/main/image (2).png?raw=true" width="500"/>

<img src="https://github.com/anukriti-bcc/Hand-Gesture-Recognition-System/blob/main/image (3).png?raw=true" width="500"/>
