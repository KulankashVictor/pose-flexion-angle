# Flexion Angle Detection

The following code is able to plot a human pose estimate on a pre-recorded video stream and get the angle between specific joints of the right arm.

## Key Aspects
- Runs on OpenCV - machine learning applicable library for computer vision
- Real time application
- Can run on CPU (later to be optimized for Nvidia GPU cores)

## On the notebook named `poseangle`
- Defined a class poseDetector with predefined joints pose, position and angle functions running on the notebook `poseangle`
- The pose detector class is initiated as directed from MediaPipe with various parameters in the class for pose detection.

## Note
We can have different classes for face, hand, pose and the angle but all of them have associated attributes hence a single class called poseDetector with diferent functions to be called later on in the notebook.
