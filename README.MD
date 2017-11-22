# Project for EEE508 
This is the second course project for EEE508 Digital Image Processing. 

## Objectives
This  android APP is developed for the general purpose of object detection and tracking. User can select an object in the scene and track that object using the bouding box around it. A demonstration of it can be found in following section.


## Applications
This APP has great potential. It can be further improved and possible applications include but not limited to: camera fixiation, security survilliance and even autonomous driving. 


## New Features

1. Feature extraction using ORB ( Oriented FAST and Rotated BRIEF):

a) keypoint of object detected using ORB
b) keypoint of object described Using ORB
c) keypoint of scene extracted
d) keypoint of scene described
e) matches of object and scene extracted by comapring object keypoint description and scene keypoint description
```
public Mat recognize(Mat aInputFrame)
```
Its theory can be found [here](http://www.willowgarage.com/sites/default/files/orb_final.pdf)

2. Finding the best matching feature given input frame, and draw a bounding box around it.

a) select best matches
b) find matches with lest distance from each other
c) transfer matches to point in color image
d) draw rectangle that bound matches
e) create output image

```

```

## How to Use
Our code is tested under Android Studio 2.3.3, Ubuntu14.04, and mobile device used is under Android 7.1.1. We used OpenCV 2.3.
Steps for reproducing our result includes:

1. install all pre-requisites.
2. Open Android studio and load the project. Make sure that there is no error message for after building the project.
3. open "debug mode" on your phone and connect it to the computer
4. Run the code and select the mobile device to execute the code
5. run the program
6. find an object click on screen
7. program start following object

If anything went wrong, a detailed instructions can be found at:
eee508f17_Project2_AndroidAppsWithOpenCV_Final.pdf

## Sample Output
![acc](../master/assets/sample_output.gif)

## Team Member Contribution
- Mohammad Farhadi Bajestani: UI, bounding box (part-2)
- Hope Yao: ORB (part-1)



