# Face Mask Detection

This project implements a real-time face mask detection system using **OpenCV**, **Keras/TensorFlow**, and **Python**. It can detect whether a person is wearing a mask or not in real-time video streams. The system is ideal for use in high-traffic areas such as malls, airports, railway stations, and stadiums, where manual checking would be inefficient and challenging.

## Features

- **Real-Time Detection**: Detects whether a person is wearing a mask or not in real-time.
- **Face Detection Box**: 
  - Green box for individuals wearing a mask.
  - Red box for individuals not wearing a mask.
- **Automatic Feedback**: Eliminates manual checking by automatically identifying mask-wearing individuals.
- **Surveillance Camera Integration**: Can be integrated with surveillance systems for monitoring compliance in crowded public spaces.

## Technologies Used

- **OpenCV**: For face detection and image processing tasks.
- **Keras/TensorFlow**: For training and deploying the deep learning model that classifies mask and non-mask faces.
- **Python**: The main programming language for implementing the project.

## How It Works

1. **Face Detection**: The system uses OpenCV’s pre-trained models to detect faces in the video stream.
2. **Mask Classification**: The detected faces are passed through a deep learning model to classify whether the person is wearing a mask.
3. **Real-Time Feedback**: 
   - A **green box** is drawn around faces where a mask is detected.
   - A **red box** is drawn for faces where no mask is detected.
4. **Accuracy Display**: The system also displays the accuracy of the mask detection in real-time.
