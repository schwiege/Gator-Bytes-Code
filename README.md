# Team Gator Bytes
This code is created by Team Gator Bytes for the BME3053C Final Project
The purpose of this code is to determine which parts of a bone Xray are affected by osteoporosis. The code utilizes image analysis techniques to isolate the affected sections
of bone and to display these sections as an overlay on top of the original image. The code also calculates an estimation of the percentage of bone affected by osteoporosis. This code is more of a proof of concept. Using Xrays for diagnosing osteoporosis is a new field and has not yet been properly done before. We attempt to change that. 


# Using our Code
To use our code, download the final_project_live_v3.mlx and open in MATLAB. 
Take one of the included image files and paste the file name into the variable I. 
An example would be I = imread('synpic59769.jpg');
The image files must be Xray images of the upper part of the femur (preferred) for the code to work. 
I would recommend only using the included images. Using other images you find off of the internet would cause
the code to not work as intended. Once the filename is included, adjust the brightness slider to the optimal number. 
In the included excel sheet are the proper brightness values for each of the included images. This step is to give our code
some more flexibility and to reduce some of the differences between each of the Xray images. Ideally the images would all be taken by the same machine and are all of the same quality. However, this is not possible so we must deal with the wide variety of Xray image qualities. 
