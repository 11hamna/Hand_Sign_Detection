This project implements a real-time sign language to text converter using OpenCV and Teachable Machine.

## About the Project
This project aims to bridge the communication gap for people who use sign language. It utilizes computer vision techniques to recognize hand gestures and translate them into corresponding text.

## Features:
Real-time processing: Analyzes hand gestures from a webcam and displays the translated text instantly.
Custom dataset: Trained on a dataset of 8-9,000 images per alphabet, ensuring model accuracy.
High accuracy: Achieves a 95% accuracy rate in recognizing hand gestures.
Platform: Designed for implementation on laptops for convenient real-time translation.
Project Structure
The project consists of two main Python scripts:

datacollection.py: This script captures hand gesture images for training the machine learning model.
test.py: This script performs real-time sign language recognition using the trained model.
## Dependencies
This project requires the following Python libraries:

OpenCV
cvzone (including HandTrackingModule and ClassificationModule)
NumPy
Math
## Installation
Install the required libraries using pip:

pip install opencv-python cvzone numpy
Use code with caution.

Download the pre-trained model files (keras_model.h5 and labels.txt) and place them in the Model folder within your project directory. 
if you want to train your own model just upload your data with labels on teachable machine and generate model

## Usage
1. Data Collection:

Run datacollection.py.
Raise your hand and perform the desired sign language gesture in front of the webcam.
Press the "s" key to capture an image of the gesture.
Repeat steps 2-3 for various signs to expand the dataset.

2. Real-time Recognition:

Ensure the pre-trained model files are placed correctly (see Installation step 2).
Run test.py.
Raise your hand and perform the sign language gesture.
The script will display the recognized text in real-time.

## Resources
Teachable Machine : https://teachablemachine.withgoogle.com
