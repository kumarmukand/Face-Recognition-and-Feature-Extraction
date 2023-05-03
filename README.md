# Face Recognition and Feature Extraction
This project is designed to detect faces in images and extract features from them using deep learning models.

# Requirements

1. Python 3.6+
2. OpenCV
3. NumPy
4. TensorFlow
5. Keras

# Installation
1. Download the Zip file from Project Repository 
2. Install the required packages:
- pip install opencv-python numpy tensorflow keras

# Usage
1. To detect faces in an image, run the following command:

- python face.py --image path/to/image.jpg

- This will generate an output image with the detected faces enclosed in green rectangles.

2. To extract features from a face, run the following command:

- python extract_features.py --image path/to/image.jpg

- This will output a feature vector for each face detected in the image.

# Models
The project uses a pre-trained deep learning model for face detection and a pre-trained convolutional neural network for feature extraction.
