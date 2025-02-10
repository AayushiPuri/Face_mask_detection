# Face Mask Detection

This project implements a real-time face mask detection system using **OpenCV**, **Keras/TensorFlow**, and **Python**. It can detect whether a person is wearing a mask or not in real-time video streams. The system is ideal for use in high-traffic areas such as malls, airports, railway stations, and stadiums, where manual checking would be inefficient and challenging.

## Key Features

- **Real-Time Detection**: Continuously monitors video streams to identify mask-wearing individuals.
- **Deep Learning-Based Model**: Uses MobileNetV2, a pre-trained neural network, for highly accurate 
classification.
- **Efficient Image Processing**: OpenCV and NumPy facilitate fast image handling and face detection.
- **Automated Decision-Making**: Draws bounding boxes around detected faces:
- Green Box: Mask detected
- Red Box: No mask detected
- **Multi-Face Recognition**: Simultaneously detects multiple faces in a single frame.
- **Surveillance Camera Integration**: Can be integrated with surveillance systems to monitor compliance in crowded public spaces.

## Technologies Used

- **OpenCV**: For face detection and image processing tasks.
- **Keras/TensorFlow**: For training and deploying the deep learning model that classifies mask and non-mask faces.
- **Python**: The main programming language for implementing the project.

## How It Works

1. **Face Detection**: Extracts faces from video input using a pre-trained deep learning model.
2. **Mask Classification**: The detected faces are analyzed using a neural network to classify whether the person is wearing a mask.
4. **Real-Time Feedback**: 
   - A **green box** is drawn around faces where a mask is detected.
   - A **red box** is drawn for faces where no mask is detected.
5. **Accuracy Display**: The system also displays the accuracy of the mask detection in real-time.

## Applications
- **Public Places**: Malls, airports, railway stations, offices, hospitals.
- **Workplaces & Corporate Use**: Ensuring employee safety in large organizations.
- **Surveillance Systems**: Can be integrated with CCTV cameras for automated monitoring.
- **Automatic Feedback**: Eliminates manual checking by automatically identifying mask-wearing individuals.

## Future Scope
- **Identity Detection**: Linking mask compliance with biometric recognition for enhanced security.
- **Extended Applications**: Adapting the model to detect facial landmarks and other safety protocols.
- **High-Resolution Support**: Integration into advanced surveillance systems for improved accuracy.

This Face Mask Detector ensures a seamless, automated solution to monitor mask compliance, reducing the need for manual checks in high-traffic areas. 🚀
