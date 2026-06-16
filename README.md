# VisionGuard: AI-Powered Online Exam Proctoring System:

## Project Overview

VisionGuard is an AI-powered online examination monitoring system designed to enhance academic integrity during remote assessments. The system uses Computer Vision and Machine Learning techniques to track candidate behavior through a webcam and identify potential cheating indicators in real time.
By leveraging MediaPipe Face Mesh, Head Pose Estimation, and Eye Gaze Tracking, the application establishes a baseline profile of a candidate and continuously monitors deviations during an examination. Suspicious behaviors such as looking away from the screen, excessive head movement, or abnormal gaze patterns can be detected and flagged automatically.

## Features

* Real-time face detection and tracking
* Head pose estimation (Yaw, Pitch, Roll)
* Eye gaze tracking and analysis
* Baseline calibration for personalized monitoring
* Real-time deviation detection
* Automated suspicious behavior monitoring
* TensorFlow-based behavioral analysis

## Technologies Used

* Python
* OpenCV
* MediaPipe
* TensorFlow
* NumPy

## Project Workflow

1. Capture candidate baseline using webcam.
2. Record head pose and gaze direction.
3. Save baseline data for reference.
4. Monitor candidate behavior during examination.
5. Compare live data against baseline.
6. Detect and flag suspicious deviations.

## Applications

* Online Examination Proctoring
* Remote Assessments
* Academic Integrity Monitoring
* E-Learning Platforms

## Project Structure

```text
VisionGuard/
│
├── main.py
├── requirements.txt
├── reference.json
├── questions/
├── synthetic_data/
├── rnn_cheating_detector.h5
├── gan_cheating_generator.h5
└── gan_no_cheating_generator.h5
```

## How to Run

```bash
pip install -r requirements.txt
python main.py
```

Select:

* **1** → Capture Baseline
* **2** → Deviation Check + Exam


