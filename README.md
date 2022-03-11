# Face Recognition System

Used to detect using Viola Jones Algorithm and recognise face using HaarCascades Classifier.

The same script may be used to perform face recognition throgh a camera or may upload the image to be recognised

![Proteus Simulation](https://user-images.githubusercontent.com/41267674/157857718-2e72c3f0-995c-4c31-9e01-6f859e8d7bbc.png)
![blockDiagram](https://user-images.githubusercontent.com/41267674/157857752-f9cf21d8-77eb-46c7-ac7a-7caa27220be1.png)

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

## RESULTS

![faceRecog](https://user-images.githubusercontent.com/41267674/157857761-f3e80448-71e7-43f5-9e03-6d5741e296ac.png)
![faceRecog1](https://user-images.githubusercontent.com/41267674/157857770-b6825472-c2b9-42d6-913a-e0fc8cd994dc.png)