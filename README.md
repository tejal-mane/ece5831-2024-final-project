# Drowsy Driver Detection System 


## Drowsiness detection is a safety technology that can prevent accidents that are caused by drivers who fell asleep while driving.

The objective of this intermediate Python project is to build a drowsiness detection system that will detect that a person’s eyes are closed for a few seconds. This system will alert the driver when drowsiness is detected.

### In this Python project, we will be using OpenCV for gathering the images from webcam and feed them into a Deep Learning model which will classify whether the person’s eyes are ‘Open’ or ‘Closed’. The approach we will be using for this Python project is as follows :

Step 1 – Take image as input from a camera.

Step 2 – Detect the face in the image and create a Region of Interest (ROI).

Step 3 – Detect the eyes from ROI and feed it to the classifier.

Step 4 – Classifier will categorize whether eyes are open or closed.

Step 5 – Calculate score to check whether the person is drowsy.

I have shared my everything work related to this project on You Tube Channel as well as on drive so that anyone can access through those links.


## Pre-recorded presentation video link
In this link, I did only presentation on ppt slides. Execution of the project is in the demo video link as below.
https://youtu.be/EnGTF2eAUjI
https://drive.google.com/drive/folders/1F4RSJeJFO7dtu-hfko8NVOpclK7n8nn2?usp=drive_link

## Presentation slides
I have shared presentation slides in both ppt and pdf format.
https://drive.google.com/drive/folders/1ZQWVqmFyTBW_KfGUM5vc6Ik7-20PbuzM?usp=drive_link


## Report
I have created a report using *LaTeX* and followed the instructions provided in the *IEEE LaTeX template*.
https://drive.google.com/drive/folders/13pDk0X4e25RvsQu7VBzsQ9PFpmu4_XMz?usp=drive_link


## Dataset
To create the dataset, I wrote a script that  captures eyes from a camera and stores in our local disk. I separated them into their  respective labels ‘Open’ or ‘Closed’. The data was manually cleaned by removing the  unwanted images which were not necessary for building the model. The data comprises around  7000 images of people’s eyes under different lighting conditions. After training the model on  our dataset, I have attached the final weights and model architecture file  “models/cnnCat2.h5”. 
I have added all dataset in this cnnCat2.h5 file.
https://drive.google.com/drive/folders/10WIJM0uWDUMb7ofNyKF4mPgGmnVnGggY?usp=drive_link

## Demo Video
Below is the demo link showcasing the execution of my project.
https://youtu.be/n7iT73K-n0U
https://drive.google.com/drive/folders/1i9yqjSzoCICsM-Oobp_yAKZf6OlEOzlJ?usp=drive_link


### Created final-project.ipynb to show that I have executed the code.


I have independently completed all the work related to this project.
For more convenient, I have added PPT and report in thi folder.