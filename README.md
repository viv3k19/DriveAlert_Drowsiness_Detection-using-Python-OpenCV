# DriveAlert Drowsiness Detection
DriveAlert Drowsiness Detection is a Python OpenCV-based system designed to prioritize road safety by monitoring driver drowsiness. This system focuses on detecting eye blinks as a key indicator of drowsiness, providing real-time alerts to drivers. By leveraging computer vision techniques and machine learning algorithms, DriveAlert Drowsiness Detection aims to reduce the occurrence of accidents caused by drowsy driving.

Drowsiness is a major concern that compromises driver attentiveness, reaction time, and decision-making abilities, increasing the risk of accidents. By continuously analyzing the driver's eye movements, this system can accurately detect patterns associated with drowsiness. When prolonged eye closures are identified, the system triggers real-time alerts, including alarm sounds, to immediately alert the driver and prevent potential accidents.

DriveAlert Drowsiness Detection utilizes the power of OpenCV, an open-source computer vision library, to track and analyze facial features, with a specific focus on the eyes. By employing Haar cascades and techniques like eye detection, the system accurately identifies and monitors the driver's eyes in real-time. The integration of alarm sounds ensures that the alerts are noticeable and effective, effectively grabbing the driver's attention and promoting timely corrective action.

With its robust functionality and reliable performance, DriveAlert Drowsiness Detection serves as a valuable tool to enhance road safety by proactively addressing the issue of drowsy driving. By providing immediate warnings and helping drivers maintain their alertness, this system plays a vital role in reducing the risks associated with driver drowsiness, ultimately making our roads safer for everyone.

## Functionality
The system uses Haar Cascades to detect faces and eyes in a video feed captured from a camera. It analyzes the eye movements and determines if the driver's eyes are closed for an extended period, indicating drowsiness. When drowsiness is detected, an alarm sound is played to alert the driver.

## Usage
* Install the required dependencies, such as cv2 and pygame.
* Download the Haar cascade XML files for face detection, eye detection, and left eye detection.
* Replace the file paths for the cascade classifiers in the script with the appropriate paths.
* Run the script.
* A video feed will open, showing rectangles around detected faces and eyes.
* If the system detects closed eyes for an extended period, an alarm sound will be played.

## Features
* Real-time monitoring of driver's eye blinks for drowsiness detection.
* Alerts the driver with an alarm sound when drowsiness is detected.
* Uses Haar cascades for accurate face and eye detection.
* Provides visual feedback by highlighting detected faces and eyes in the video feed.

## Prerequisites
* Python 3.10 or ^
* OpenCV library
* Pygame library
* Haar cascade XML files for face detection, eye detection, and left eye detection

## Technologies Used
* Python
* OpenCV
* Pygame

## How to Run
* Ensure you have Python installed on your system.
* Install the necessary dependencies by running `pip install opencv-python pygame`
* Download the Haar cascade XML files for face detection, eye detection, and left eye detection.
* Clone or download the script from the repository.
* Replace the file paths for the cascade classifiers in the script with the appropriate paths on your system.
* Run the script using the command python DrowsinessDetection.py.
* A window will open displaying the live video feed with detected faces and eyes.
* If drowsiness is detected, an alarm sound will be played to alert the driver.
* Press 'q' to quit the program.
## Screenshot

![Capture](https://github.com/viv3k19/DriveAlert_Drowsiness_Detection-using-Python-OpenCV/assets/82309435/dc3752d2-8279-4780-86c7-4824d9254dad)

# Project Creator
* Vivek Malam - Feel free to contact me at viv3k.19@gmail.com for any questions or feedback.
