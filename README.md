## Attendance Portal using Artificial Intelligence
This project is an attendance portal that uses facial recognition to mark attendance. The system detects faces in real-time through the webcam and matches them with a pre-defined set of images. The names of the recognized faces are logged in a CSV file along with the time of their arrival.

## Dependencies
- Python 3.x
- OpenCV (cv2)
- Numpy
- Face_recognition

## Installation
- Clone this repository
- Install the required dependencies
- Place the images of the people whose attendance you want to track in the photos folder.
- Run the program


## Usage

When the program runs, the camera feed opens up, and faces in the frame are detected.

The system compares the detected faces with the pre-defined set of images and marks attendance for the recognized faces with the help of the HOG Algorithm(Histogram of Oriented Gradients) and SVM Classifier(Support Vector Machine). The deep learning library- face_recognition- is implemented in the code. face_recognition is a deep learning library used for face recognition tasks. It is built on top of deep learning frameworks like TensorFlow and Caffe, and uses convolutional neural networks (CNNs) to perform facial recognition. It uses a pre-trained model to generate facial encodings which can be used to compare and identify faces in images or videos.

The names of the recognized faces are logged in a CSV file named as the current date.
