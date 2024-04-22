# Driver Drowsiness Detection using CNN

## Overview
This project aims to detect driver drowsiness in real-time using computer vision and deep learning techniques. The system analyzes the driver's facial features captured through a camera installed in the vehicle to detect signs of drowsiness. It utilizes Convolutional Neural Networks (CNN) implemented with Keras and TensorFlow for efficient feature extraction and classification.

## Dependencies
- Python 3.x
- OpenCV
- TensorFlow
- Keras
- NumPy

## Installation
1. Clone the repository:
2. Install dependencies:

## Usage
1. Run the `detect_drowisiness.py` script:
2. 2. The script will start capturing video from the webcam or the specified video source.
3. It will analyze the facial landmarks and classify the driver's state into either "alert" or "drowsy" based on eye closure and head position.
4. If the system detects drowsiness, it can trigger alerts such as sound alerts or warnings displayed on the screen.

## Dataset
The model is trained on a dataset consisting of images and videos of drivers in both alert and drowsy states. The dataset used for training and testing the model should ideally be diverse and representative of real-world scenarios.

## Model Architecture
The CNN model used in this project typically consists of convolutional layers followed by max-pooling layers, fully connected layers, and output layers. The exact architecture may vary depending on experimentation and fine-tuning.

## Performance
The performance of the drowsiness detection system can be evaluated based on metrics such as accuracy, precision, recall, and F1 score. Continuous monitoring and feedback from real-world usage are essential for improving the system's performance and reliability.

## Future Improvements
1. Integration with vehicle systems for real-time alerts and notifications.
2. Incorporating additional features such as yawning detection or monitoring physiological signals.
3. Optimizing the model for deployment on embedded systems or edge devices.
4. Enhancing the user interface for better usability and customization options.

## Contributors
- [Rishikesh Shyam R S](https://github.com/rishikeshshyam)

## License
This project is licensed under the [MIT License](LICENSE).


