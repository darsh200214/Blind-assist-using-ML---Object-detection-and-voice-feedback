# Blind-assist-using-ML---Object-detection-and-voice-feedback

With the recent rapid development of information technology (IT), a lot of research has been carried out to solve inconveniences in everyday life, and as a result, various conveniences for people have been provided. Nevertheless, there are still many inconveniences for the visually impaired. The greatest inconveniences that a blind person feels in everyday life include finding information about objects and indoor mobility problems. They have difficulty recognizing simple objects, and it is not easy to distinguish objects that have similar forms. Previous studies included object analysis using ultrasonic sensors. However, with these methods, it is difficult to know exactly where an object is located, especially in the presence of obstacles. In this project, we analyze accurate object information and obtain a location using a deep learning object recognition technique. In addition, voice recognition and voice guidance technologies are synthesized so the visually impaired can know the location of the objects they want to find by speaking to the system.


![overview](https://user-images.githubusercontent.com/98044958/193468428-215a5295-18b7-4227-afe3-52bf1f53a3c0.png)


Steps to execute :

1. Download the code in a zip file from github repository
2. Extracted the downloaded zip file
3. Download yolov3.weights file from the below link

   This file was too large for github repository
   
   Hence yolov3.weights can be downloaded from the below link :
   
   https://drive.google.com/file/d/1OyO0CACnyFzz5qAwhEX9idpbrqAJx_Wo/view?usp=sharing
   
4. Cut paste the downloaded file inside yolo-coco folder 
5. Open cmd prompt inside the source code folder and execute the file with the following command

   python script.py --image images/dog.jpg --yolo yolo-coco
