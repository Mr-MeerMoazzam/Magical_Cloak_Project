# Magical_Cloak_Project
Most of us heard about the Harry Potter series. In that series, he used an invisible cloak that made him invisible...! Are you wondering how they made invisible cloaks.....? That’s not as tough as rocket science to build this invisibility cloak.
I am not building it in real way it’s all about graphical tricks with openCV and python to make things invisible in front of webcam.
The main objective of this project is to hide the object that is behind a specific colored cloak.

Pipeline of the project is given below:


![pipline](https://user-images.githubusercontent.com/98279854/170553337-d42efc77-eece-47e8-9d47-cdf2a443b6be.PNG)


This figure shows the steps to be followed in order to generate the augmented
output. Firstly we will set an initial frame for the background then take input from the
camera continuously and detect color from the frame and create a mask of it and
then apply bitwise operations on it for mixing the frame and the mask. At last, we will
merge the images after applying bitwise operations on the initial frame and the
current frame then the image is final augmented output.


Flow Chart of the Project is givem below:




![flowchart](https://user-images.githubusercontent.com/98279854/170554204-aa5e0b9a-c872-429e-aa99-0fa2057649be.PNG)

