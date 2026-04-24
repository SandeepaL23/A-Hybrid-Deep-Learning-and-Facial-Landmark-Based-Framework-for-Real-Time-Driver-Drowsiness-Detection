# A-Hybrid-Deep-Learning-and-Facial-Landmark-Based-Framework-for-Real-Time-Driver-Drowsiness-Detection
AI-based driver drowsiness detection system using Deep Learning and facial landmarks (EAR, MAR) for real-time alerts.

## Project Overview
Road accidents caused by driver fatigue are a serious problem. This project aims to solve that by building a real-time drowsiness detection system.

It uses a combination of Deep Learning and facial landmark analysis to monitor the driver’s condition. By tracking eye closure and yawning, the system can detect early signs of drowsiness and alert the driver instantly to prevent accidents.

## Objectives
1. Detect drowsiness in real-time using a webcam
2. Monitor eye closure using Eye Aspect Ratio (EAR)
3. Detect yawning using Mouth Aspect Ratio (MAR)
4. Use a CNN model (MobileNetV2) for classification
5. Trigger alerts when signs of fatigue are detected

## Technologies Used
1. Python
2. OpenCV
3. TensorFlow / Keras
4. MediaPipe
5. NumPy

## Dataset
The dataset used for training the model is available on Kaggle:
   https://www.kaggle.com/datasets/yasharjebraeily/drowsy-detection-dataset

Note:
The dataset is not included in this repository due to its large size. You can download it directly from the link above.

## How the System Works
1. The webcam captures live video of the driver
2. MediaPipe detects the face and extracts key landmarks
3. The system calculates:
    Eye Aspect Ratio (EAR) to detect eye closure
    Mouth Aspect Ratio (MAR) to detect yawning
4. The captured face is passed to a trained CNN model
5. All results are combined using a weighted approach
6. If drowsiness is detected, an alert is triggered immediately


## Key Features
1. Real-time driver monitoring
2. Combination of Deep Learning + facial analysis
3. High accuracy (~96%)
4. Lightweight and efficient system
5. Instant audio alert mechanism

## Results
1. Achieved strong accuracy using MobileNetV2
2. Improved detection reliability using multiple features
3. Reduced false alerts with hybrid approach

## Future Improvements
1. Develop a mobile/camera based IoT application version
2. Improve performance in low-light environments
3. Integrate with smart vehicle systems

## References
Kaggle Dataset
Research papers on driver drowsiness detection


### This project demonstrates how AI can be used to improve road safety by detecting fatigue in real time.
