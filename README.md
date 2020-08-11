# realtime-faceid

![License](https://img.shields.io/github/license/Rohith-hacker/realtime-faceid)
![Issues](	https://img.shields.io/github/issues/Rohith-hacker/realtime-faceid)

FaceID

This is an implementation of face detector and recognizer which can identify the face of the person showing on a IOS camera.

Image preprocessing: face detection, alignment and resizing. Built a database containing embeddings of identity images Computed euclidean distance of embeddings between tested and identity faces to perform identity recognition image

For Face Detection (in real time or an image): we show how to implement face detection using OpenCV or Multi-task CNN;

For Face Recognition (in real time or an image): we use a deep neural network, the model we use is based on FaceNet, which was published by Google in 2015 and achieved 99.57% accuracy on a popular face recognition dataset named “Labeled Faces in thae Wild(LFW)". You can find its open-source Keras version here and Tensorflow version here, and play around to build your own models.

# There are three steps for face recognition:
1. Collecting face data (your face pictures) and labels and save to dataset folder. 
2. Input face data and labels into model to train a recognition model.
3. Download the model 
4. Use this template on your model to perform face recognition on IOS device.

# Instructions:
1. Download this repository as zip file and unzip it to a folder.
2. perform a Pod Install in that folder (this installs all the required packages)
3. Open Xcode and run the project file.
4. You can import your custom model in the model folder and then perform the face recognition on your data.
