# AI-IP-VIRTUAL-PEN
This pen can write virtually without keyboard and mouse. It can save the hardware cost and also save materials like paper and contribute to environment.



Ever wanted to draw your imagination by just waiving your finger in air.
In this post we will learn to build an Air Canvas which can draw anything on it by just motion of our hands and noticing the landmark on the hand knuckels.
A very beautiful project for resume of machine learning people. 
We will be using the computer vision techniques of OpenCV to build this project. 
The preffered language is python due to its exhaustive libraries and easy to use syntax but understanding the basics it can be implemented in any OpenCV supported language.





Algorithm
1.Start reading the frames and convert the captured frames to HSV colour space.(Easy for colour detection)

2.Prepare the canvas frame and put the respective ink buttons on it.

3.Adjust the values of teh mediapipe intilization to detect one hand only.

4.Detect teh landmarks by passing the RGB frame to the mediapipe hand detector

5.Detect the landmarks, find the forefinger coordinates and keep storing them in the array for successive frames .(Arrays for drawing points on canvas)

6.Finally draw the points stored in array on the frames and canvas .

Requirements: python3 , numpy , opencv, mediapipe installed on your system.


![image](https://user-images.githubusercontent.com/96643131/227604019-99e8d478-0b4d-449c-9c9e-8579cfac438d.png)

![image](https://user-images.githubusercontent.com/96643131/227604260-89752fc3-018b-4b95-ba5a-59f874bb9d91.png)
