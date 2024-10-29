# Proactive Road Safety: Real-time Driver Drowsiness Detection

This project focuses on real-time driver drowsiness detection to enhance road safety. By leveraging deep learning and computer vision, the system detects signs of driver drowsiness and provides alerts to minimize potential accidents. The solution uses TensorFlow, Keras, OpenCV, and Python with facial landmark detection techniques.

## Table of Contents
1. [Overview](#overview)
2. [Features](#features)
3. [Installation](#installation)
4. [Usage](#usage)
5. [How It Works](#how-it-works)

---

### Overview

Driver drowsiness is a significant cause of road accidents globally. This project provides a proactive approach to road safety by detecting drowsiness using facial landmarks in real time. It uses a camera to monitor the driver’s eye and head movements, processing the data to detect signs of fatigue or inattention.

### Features

- Real-time facial landmark detection
- Eye and head movement analysis
- Audio alerts using text-to-speech to warn the driver
- Lightweight and suitable for real-time application on devices

### Installation

1. **Clone the Repository**
```bash
git clone https://github.com/VeerankiBhargavi/driver-drowsiness-detection.git
cd driver-drowsiness-detection
```

  
OR


```bash
git clone https://github.com/sanakhaname12/driver-drowsiness-detection.git
cd driver-drowsiness-detection
```


 ### Usage

1. **Run the Main Script**
   ```bash
   python "drowsiness detection.py"

Ensure the camera is accessible.
An audio alert will sound when drowsiness is detected.
Parameters
Adjustable thresholds for eye aspect ratio (EAR) and head position.
Modify these in the configuration file as needed.


### How It Works


The project employs facial landmarks detection to monitor driver drowsiness through two main techniques:

Eye Aspect Ratio (EAR): Measures the openness of the eyes; lower EAR values indicate closed eyes.
Head Position Monitoring: Detects if the driver’s head is tilting or facing away from the road.
A combination of these indicators triggers an alert using text-to-speech functionality provided by pyttsx3.
