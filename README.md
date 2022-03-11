# Face Recognition System

Used to detect using Viola Jones Algorithm and recognise face using HaarCascades Classifier.

The same script may be used to perform face recognition throgh a camera or may upload the image to be recognised

# Edge Proccesing
The Python Script can be run for a definite period on Raspi-OS and can relay the processed-data to the server located far away

## Tech Used:
- Raspberry Pi3B
- Raspi Webcam
- Python3

## Steps to run in DEV Environment

- pip -r requirements.txt
- Run the face_datasets.py file and collect the sample images of the target
- Run the training.py and train the model with the data
- Run the face_recognition.py and perform live-detection of face through the camera

**Note: Need to install Windows SDK Kit, CMake**