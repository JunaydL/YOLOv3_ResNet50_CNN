# YOLOv3_ResNet50_CNN
These are some of my practice codes to see how to combine Yolov3 and ResNet50 backbone

These files contain my work on the YOLOv3-Gassian prediction AI. 
I've attempted to change the Darknet53 backbone to a Resnet 50 backbone. 
There are two demo files. The demo1 jupyter file is used to run the model wthout any weights. 
The demo2 jupyter file is used to add multiple weights to the AI model. 
Usually since the model is YOLOv3 it will try to prioritize th YOLOv3 weights over all other weights. 

There are two pictures. 
One shows the original results of the Darknet53 backbone and the other image holds the Resnet53 backbone results.

The yolov3.py file contains both the Darknet53 backbone along with my other 
attempts and notes at adding in the ResNet50 backbone. 

The file "demo.png" will have the current image produced when either jupyter file is ran. 
You can use this to compare between the original results I have recieved. 

Lastly, there is a file called "ImageNet_Categories.txt." 
I used this to list out all the ImageNet categories that could be labeled to see if the ImageNet weights 
would work. You can use these if you are trying to add the ImageNet weights for the model to use. 

All other needed files from the original YOLOv3_Gaussian Prediction file from Motokimura is in here as well.
