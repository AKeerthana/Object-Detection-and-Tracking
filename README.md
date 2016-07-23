# Object-Detection-and-Tracking
Project developed in python to develop an object detection system using OpenCV software. The main functionalities displayed in this project include Object Detection based on color that is to classify objects in images according to colour , Pedestrian detection  , Human face detection, Vehicle motion Detection from a video file which can be used to detect traffic in a particular area.


About the project
The purpose of doing this project is not basically just to detect objects in an image but also for some other purpose which are: 
i)	To utilize the object’s region in a digital images. 
ii)	To leverage positive object’s classifier using Haar-Training.
iii)	To develop an object detection system using OpenCV software.
Commands used to train the Haar-Cascade are as follows: - Commands :
1.	opencv_createsamples –img b.jpg –bg bg.txt –info info.lst –pngoutput info –maxxangle 0.5 –maxyangle -0.5 –maxzangle 0.5 –num 1110
2.	opencv_createsamples –info info/info.lst –num 1110 –w 20 –h 20 –vec positives.vec
3.	opencv_traincascade –data data –vec positives.vec –bg bg.txt –numPos 1110 –numNeg 1000 –numStages 8 –w 20 –h 20.


