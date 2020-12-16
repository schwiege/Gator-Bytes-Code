# Gator-Bytes-Code
Team Gator Bytes code for the BME3053C Final Project
The purpose of this code is to determine which parts of a bone Xray are affected by osteoporosis. The code utilizes image analysis techniques to isolate the affected sections
of bone and to display these sections as an overlay on top of the original image. This code is more of a proof of concept. Using Xrays for diagnosing osteoporosis is a new field
and has not yet been properly done before. We attempt to change that. 


# Using our Code
To use our code, take one of the included image files and paste the file name into the variable I. 
An example would be I = imread('filename.jpg');
The image files must be Xray images of the upper part of the femur (preferred) for the code to work. 
I would recommend only using the included images. Using other images you find off of the internet would cause
the code to not work as intended. Once the filename is included, adjust the brightness slider to the optimal number. 
In the included excel sheet are the proper brightness values for each of the included images. This step is to give our code
some more flexibility and to reduce some of the differences between each of the Xray images. 
