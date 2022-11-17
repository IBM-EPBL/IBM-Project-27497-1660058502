# **IBM-Project-27497-1660058502**
# **A Gesture-Based Tool For Sterile Browsing Of Radiology Images**
## **TEAM:**

 Team ID :PNT2022TMID28589

 Team Leader : ADHITYA VARMAN V - 312819205003

 Team Member : KRISHNA G - 312819205015

 Team Member : MOHANA SUNDRAM V - 312819205022

 Team Member : VAIBHAV U - 312819205045
 
 ## INTRODUCTION :
 
   - Humans are able to recognize body and sign language easily. This is possible due to the combination of vision and synaptic interactions that were formed along brain development . In order to replicate this skill in computers, some problems need to be solved: how to separate objects of interest in images and which image capture technology and classification technique are more appropriate, among others.
   
   - In this project Gesture based Desktop automation ,First the model is trained pre trained on the images of different hand gestures, such as a showing numbers with fingers as 1 ,2,3,4 . This model uses the integrated webcam to capture the video frame. The image of the gesture captured in the video frame is compared with  the Pre-trained model and the gesture is identified. If the gesture predictes is 1 then images is blurred;2, image is resized;3,image is rotated etc.


## Project Objectives 
  Know fundamental concepts and techniques of Convolutional Neural Network.
  
  Gain a broad understanding of image data.
  
  Know how to pre-process/clean the data using different data preprocessing techniques.
  
  Know how to build a web application using Flask framework.
## Project Flow
  User interacts with the UI (User Interface) to upload the image as input

  Depending on the different gesture inputs different operations are applied to the input image.

 Once model analyses the gesture, the prediction with operation applied on image is showcased on the UI.
 
 ###### To accomplish this, we have to complete all the activities and tasks listed below :-

 - Data Collection :

   - Collect the dataset or Create the dataset

 - Data Preprocessing :

    - Import the ImageDataGenerator library

    - Configure ImageDataGenerator class

    - Apply ImageDataGenerator functionality to Trainset and Testset

- Model Building :

    - Import the model building Libraries

    - Initializing the model

    - Adding Input Layer

    - Adding Hidden Layer

    - Adding Output Layer

    - Configure the Learning Process

    - Training and testing the model

    - Save the Model

- Application Building :

     - Create an HTML file

     - Build Python Code

# Project Structure :

 Project folder which contains files as shown below
 
 ![image](https://user-images.githubusercontent.com/100921448/201666828-104523cc-1abe-4df6-948b-622e6995545e.png)


   - Dataset folder contains the training and testing images for training our model.

   - We are building a Flask Application which needs  HTML pages stored in the templates folder and a python script app.py for server side scripting

   - We need the model which is saved and the saved model in this content is gesture.h5

   - The static folder will contain js and css files.

   - Whenever we upload a image to predict, that images is saved in uploads folder.

# Prerequisites :

## Anaconda Navigator :

 - Anaconda Navigator is a free and open-source distribution of the Python and R programming languages for data science and machine learning-related applications. It      can be installed on Windows, Linux, and macOS. Conda is an open-source, cross-platform, package management system. Anaconda comes with so very nice tools like          JupyterLab, Jupyter Notebook,QtConsole, Spyder, Glueviz, Orange, Rstudio, Visual Studio Code. For this project, we will be using Jupiter notebook and spyder.To        install Anaconda navigator and to know how to use Jupyter Notebook a Spyder using Anaconda watch the video given here. [https://youtu.be/5mDYijMfSzs]

## Python packages :
  - open anaconda prompt as administrator 

  - Type “pip install tensorflow” (make sure you are working on python 64 bit) 

  - Type “pip install opencv-python”

  - Type “pip install flask".

## Technical Architecture:

![image](https://user-images.githubusercontent.com/100921448/196022303-129fc359-0d5c-451f-953a-b7e71004a709.png)
