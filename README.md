# Face Detection using OpenCV Python
---
Face detection is the first and foremost step for [face recognition](https://www.kaspersky.com/resource-center/definitions/what-is-facial-recognition). It is used to detect faces in images. Face detection is a part of object detection and can be used in many areas such as security, bio-metrics, law-enforcement, entertainment, personal safety etc.

Face detection is an [AI-based](https://www.ibm.com/cloud/learn/what-is-artificial-intelligence) computer technology that can identify and locate the presence of human faces in digital photos and videos. Due to the advancements in face detection technology, It is now possible to detect faces in an image or video, regardless of head pose, lighting conditions, and skin tone.

This repository contains code to implement face detection using OpenCV Python.

## Description:
---
This project uses OpenCV Haar cascades for face detection. Haar cascade classifier is a Machine learning object detection program that identifies objects in an image and video. Even though it is has been over a decade since Haar cascade classifiers have been introduced, they are still widely used in object detection. 

Today there are many other object detection algorithms but none of them can beat Haar cascade at one thing, its the speed of processing images. More detailed information about Haar cascade classifiers can be found [here](https://www.cs.cmu.edu/~efros/courses/LBMV07/Papers/viola-cvpr-01.pdf).

## Structure of the repository:
---
Github Repository contains the following structure.
- ***faceDetection.py*** - This is the source file which contains code for facedetection using OpencvPython.
- ***haarcascade_frontalface_default.xml*** - This is the .xml file which is basically a pre-trained model which detects faces in an image.
You can download much more pre-trained model from [here](https://github.com/opencv/opencv/tree/master/data/haarcascades).
**To download follow belo steps**.
    - Click on the above link, it will take you to the github page.
    - Click on the haarcascade you want to try.
    - Then click on **raw**.
    - **Right** click on your mouse.
    - Click on **save as**.
    - save it in your projects working directory.

- ***Readme.md*** - This contains details about the project repo.
- ***images*** - This is a directory that contains images of sample output.

## How to Run the script:
---
- Goto to my github repository.
- click on ***code***.
- click on ***Download zip***.

You can also clone the repository to your machine, to clone the repository execute the below command on your terminal.

**Note** : *Before executing the below command navigate to the directory where you want to clone the repo. You can use cd command to change directory on your machine.*
<p align = 'center'><b>git clone https://github.com/SuhasBRao/FaceDetection</b></p>
- After cloning the repository, to run the script navigate to the path where you have cloned and execute the command on your terminal.
<p align = 'center'><b>python faceDetection.py</b></p>

#### ***NOTE***: Make sure you have installed OpenCv on your machine.

## Sample Output:
---

Here's a sample output after running faceDetection.py

![Face detection](/images/Face_detection.png)