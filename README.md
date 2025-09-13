# Face-Detection-
With OpenCV simple Face Recognition Python Project

#Face Detection with OpenCV and DroidCam

This project demonstrates a real-time face detection system using Python and OpenCV. The camera input is taken from DroidCam (Android phone acting as a webcam). The system detects human faces from the live video stream and highlights them with rectangles.

Workflow:

1.Load Haar Cascade Classifier (haarcascade_frontalface_default.xml) to detect frontal faces.

2.Capture video frames using DroidCam (via cv2.VideoCapture(1)).

3.Convert frames to grayscale for better detection performance.

4.Apply detectMultiScale to locate faces of different sizes.

5.Draw rectangles around detected faces.

6.Display live video with detections.

7.Press q to quit safely.

Features:

Works with both PC webcam and DroidCam virtual webcam.

Real-time face detection.

Lightweight and easy to run.

Can be extended into a full face recognition system.
