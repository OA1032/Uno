# Uno - Card Recognition Project

# This project was completed using a windows machine and compatability has not been checked on otheer systems such as Linux and MacOS.

# Created using Jupyter notebooks

The task: - 

Write code for recognising cards from the game UNO. The program should be able to receive input
either from 1) file or 2) a standard camera, and identify cards in the image or frame (one at a time).
  
You can implement specific computer vision code for recognising some features algorithmically, but
you are encouraged to use more general code based on machine learning techniques.  
 
You can use any function from OpenCV or from libraries included in the Anaconda Python distribution.
Keep in mind that sometimes implementing a function yourself can be faster / easier than making
something external work as you wish. If you find useful information / examples on the web, please
cite appropriate references, including repository pages.
Include an option (or alternative code) for running the program on saved files rather than camera
stream.  

Please submit all images used to train and test the system. To start, you can use the images
provided in the file images.zip.
The code should easily run on a standard platform. Any important information related to code
execution, user interface, help, etc. has to be included in a readme file.

# Currently the ML model can only recognise the number 4 and 6 

# Colour limits will need to be changed to make sure the correct colours are detected adequately. Depending on the place the camera capture is taking place the camera serveral other factors the colour limit values will need to be adjusted.

# File Pathways will need to be adjusted based on where the images are saved

# Execution 

In order to use this program you must: - Run the Notebook cells from top to bottom 

# Download the Asst2_Olu-Final folder and the necessary dependecies then run the cells from top to bottom

# Right now only colour recognition has been implemented on video.

# The main code is in A2_Uno. 

# The saved model that is used is MLP.sav

Install the necessary dependencies using your command window. 
  
  OpenCV2,  
  
  Numpy,
    
  Matplotlib,
    
  pickle,
    
  sci-kit learn, 
    
  pandas,
    
  skimage

# Currently Partially finished

Versions 

0.7 ---- Include digit estimation based on convexity
  
0.6 ---- Included machine learning using MLP to predict the digit of the image based on thee MNIST data set
  
0.5---- Included machine learning using SVC to predict the digit of the image based on thee MNIST data set
  
0.4 ---- Identifying the number contour
  
0.3 ---- Identifying contours and cropping colours
  
0.2 ---- show all the images in the uno images folder
  
0.1 ---- View and display images

# Future implementations 

Include a save image option to run all this code from an image saved from the camera stream.

Properly tune the parameters of the MLP 

Use a more Appropriate Dataset, preferabbly one that is centered around Uno cards. 

# References 

StackOverFlow

MachineLearningMastery

# Other sources listed in the comments of the code
