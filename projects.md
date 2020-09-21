---
layout: default
permalink: /projects/
---


Projects
====================

* ## **Explainable AI (XAI) - Some fun with visualizations:** <br>
This small project aims at visualizing the important features of an image that contributes to the final classification label. Saliency maps and Grad-Cam visualizations are studied. Used keras visualization library for creating visualizations. <br>
Document: [XAI.pdf](https://drive.google.com/file/d/1J4Kbe377SQ9HRAI8c_Arlpzw-SdcCQ8N/view?usp=sharing) <br>
Github: [https://github.com/ankurbhatia24/XAI](https://github.com/ankurbhatia24/XAI) <br>
<img src="/assets/Projects/xai-displayImage.png" allign="center" height="450" width = "800"> <br> 


* ## **Flask Based Whatsapp Application with Twilio:**  <img src="/assets/Projects/new_small.gif"> <br>
This project helps to calculate the amount of money people are donating to PM-CARES fund (Prime Minister's Citizen Assistance and Relief in Emergency Situations Fund ) during the period of Lockdown.
This WhatsApp application allows the users to send a screenshot or a pdf, as a WhatsApp message, of the payment done to the fund from 9 specific locations. The application takes the user media input and processes the image to evaluate the amount automatically using Computer Vision Techniques.
Also, this application has a functionality of finding weather the user has downloaded the "Arogya Setu" App in his mobile device or not. For this, the user has to send the screenshot of his mobile screen where the app is present. <br>
Github Repo: [https://github.com/ankurbhatia24/Whatsapp-Twilio-Backend](https://github.com/ankurbhatia24/Whatsapp-Twilio-Backend) <br>
Application Video: [https://bit.ly/whatsapp-twilio](https://www.youtube.com/watch?v=ABdhxErtkH4) <br>
**Test Database**
You can check the queries and its result images at - [Database.csv](https://docs.google.com/spreadsheets/d/15K4Rc39m7zxl5mPylbLGwgRBCokYAhoOCEfT6Ly1NAA/edit?usp=sharing). It is just a testing db to check errors in the detection process. <br>
1. Application Poster
2. Payment Gif
3. Arogya-Setu App Detection Gif
4. Dashboard Gif <br>
<img src="/assets/Projects/WhatsappTwilio.png" allign="center" height="450" width = "800"> <br> 
<img src="/assets/Projects/WhatsappPayment.gif" height="500" width="280">  <img src="/assets/Projects/WhatsappApp.gif" height="500" width="280"> <img src="/assets/Projects/WhatsappDashboard.gif" height="500" width="280">  

* ## **Reddit Exploratory Data Analysis and Flair Prediction Application:**
This project consist of Flair Prediction on reddit posts of r/india. (The term flair, used in some subreddits for 'categorizing' posts submitted by users). EDA has been performed on the subreddit data collected. PRAW: The Python Reddit API Wrapper is used for data collection of the following flairs: <br> "AskIndia", "Coronavirus", "Non-Political", "Scheduled", "Photography", "Science/Technology", "Politics", "Business/Finance", "Policy/Economy", "Sports", "Food", "AMA". <br>
**EDA:** <br>
1. Most Popular Words (WordCloud)
2. Posts with less than 10 votes (histogram)
3. Most Popular Posts (BarPlot)
4. Most Commented Posts (Barplot)
5. No. of Comments vs Score (Regression Plots)
6. Top 10 Authors
7. Text Cleaning and Analysis
8. Bag of Words on 2 Posts of same Flair
9. XG Boost Classifier
10. Feature Importance for Flair Prediction, etc. <br>
[**Code - IPYNB**](https://github.com/ankurbhatia24/Reddit_EDA/blob/master/IPYNB/EDA.ipynb) <br>

**Prediction Algorithm includes:** <br>
1. Logistic Regression (sklearn: CountVectorizer -> TFIDF Transformer -> Logistic Regression)
2. SVM (sklearn: CountVectorizer -> TFIDF Transformer -> SVM)
3. Naive Bayes (sklearn: CountVectorizer -> TFIDF Transformer -> Naive Bayes)
[**Code - IPYNB**](https://github.com/ankurbhatia24/Reddit_EDA/blob/master/IPYNB/Testing%20basic%20ML%20Models.ipynb)
4. 1-D Convolution (Tensorflow/Keras: Word2Vec -> GloVE embeddings -> 1-D Convolution)
5. LSTM (Tensorflow/Keras: Word2Vec -> GloVE embeddings -> LSTM)
6. Bidirectional LSTM (Tensorflow/Keras: Word2Vec -> GloVE embeddings -> Bidirectional LSTM) <br>
[**Code Repo**](https://github.com/ankurbhatia24/Reddit_EDA/blob/master/IPYNB/Data_pre-procesing%20and%20Model%20Evaluation.ipynb) <br>
<img src="/assets/Projects/RedditEDA1.gif" height="191" width="640"> 

**Application:** 
1. Flask Web Application with a simple form. It takes the link of reddit post (r/india) and returns back the Flair.
2. Also includes a rest api which can predict the flairs of all the links placed in a text file and returns a json object of the predicted flairs.

* ## **Multi-modal Human Emotion Recognition: - 2019-2020:** <br>
This research work is focused on studying the capability of robots to understand human emotions in real-time. Understanding emotions will allow the systems to adapt according to the responses and behavioral patterns. If this happens in a reasonable sense of accuracy, then we would be expecting artificial agents to be our cognitive-consulting partners in our everyday life. <br>
For multimodal emotion recognition: we divided the dataset into 3 parts. The text part (text utterances), the audio part (audio utterances), and the Video part (Face model). We use deep learning models for classifying the emotions into 7 categories - **Anger, Disgust, Fear, Joy, Neutral, Sadness, Surprise**.<br>
Synopsis: [MMHER Synopsis](https://docs.google.com/document/d/17qSOclmcoHCBSjNucMovgoVX1fKSyFwkWQ1cJM8CnGE/edit?usp=sharing) <br>
Code: [https://github.com/ankurbhatia24/MULTIMODAL-EMOTION-RECOGNITION](https://github.com/ankurbhatia24/MULTIMODAL-EMOTION-RECOGNITION) <br>
<img src="/assets/Projects/MELD1.PNG" height="350" width="700"> <br>
<img src="/assets/Projects/MELD2.gif" height="180" width="600">

* ## **[In-Progress]Deep Learning for Single Image Super Resolution (SISR):** <img src="/assets/Projects/workinprogress_small.gif"> <br>
Proposal: [Proposal Link](https://docs.google.com/document/d/1t1yGBqy-M5kxg7aG_Twj5Qoip79vGNDXMfcxzja07JY/edit?usp=sharing) <br>
Github: [https://github.com/ankurbhatia24/image-super-resolution](https://github.com/ankurbhatia24/image-super-resolution) <br>

* ## **[In-Progress] Crazyflie 2.1 Autonomous motion:** <img src="/assets/Projects/workinprogress_small.gif"> <br>
Project to be done: Stable autonomous motion using Vicon Markers. <br>
Checkout Crazyflie ROS packages here - [https://github.com/whoenig/crazyflie_ros](https://github.com/whoenig/crazyflie_ros) <br>
Teleoperation Video: [https://www.youtube.com/watch?v=Dy30Q3vTisA](https://www.youtube.com/watch?v=Dy30Q3vTisA) <br>
<img src="/assets/Projects/CrazyflieTeleoperation.gif" height="300" width="600"> 



* ## **Eyantra Robotics Competition - 2018-19:** <br>
This project is a part of Eyrc Robotics Competition 2019. 
1. Control of Autonomous bot including Robot chassis Designing, Raspberry Pi, Arduino, Color Image Processing, ArUco Detection and Path Planning.
2. Design of Robotic Arm and stacking mechanism for pick, place and stacking.
3. Implemented FSM and PID feedback control algorithms for accurate line following. <br>
Poster Presented (CHASCON 2019): Line Follower using Finite State Machine [http://bit.ly/LFR_FSM_paper](http://bit.ly/LFR_FSM_paper) <br>
Video Presentation: [https://www.youtube.com/watch?v=FhUvQlrLWxc&t=135s](https://www.youtube.com/watch?v=FhUvQlrLWxc&t=135s)<br>
Code Repo: [https://github.com/ankurbhatia24/Eyrc2019](https://github.com/ankurbhatia24/Eyrc2019) <br>
<img src="/assets/Projects/EYRCTheme.png"> <br>
<img src="/assets/Projects/EYRCVideo.gif" height="376" width="600">

* ## **World Robot Olympiad - National Level, Kolkata, India - 2016:** <br>
Designed a recycling plant robot that collects and segregates the waste into its respective containers using LEGO Mindstorms NXT. It includes line-following, color detection and actuator designing. <br> 
The competition was divided in 4 rounds: <br>
1. Selection Round, Science City, Lukhnow - This was the first time we were introduced with the NXT kits. There were 9-10 teams from various different schools, all teams were taught the basics of rotation of wheels, speed controls and Ultrasonic sensor. A small selection competition was conducted where a path needs to be followed by the robot avoiding obstacles (Task Duration - 30-45 minutes). We were able to make in the top 2 teams (We were 2nd) and got selected for the Free kit sponsorship.
2. Next round was regional round, City Montessori School, Lucknow - This was the full task round, teams from various regional cities participated. We made it to the nationals, though our robot was only modified to work half the pathway on flex with fick and place of the containers.
3. Third was the National Round, Netaji Indoor Stadium, Kolkata - Theme Rap the Scrap, We ranked 13 in the national level. <br>
Video: [https://www.youtube.com/watch?v=mVLkh1UcLbE](https://www.youtube.com/watch?v=mVLkh1UcLbE) <br>
<img src="/assets/Projects/WRO.gif" height="330" width="500"> <img src="/assets/Projects/WRO7.jpeg" height="330" width="400"> <br>
<img src="/assets/Projects/WRO1.jpeg" height="330" width="290"> <img src="/assets/Projects/WRO2.jpeg" height="330" width="290"> <img src="/assets/Projects/WRO3.jpeg" height="330" width="300"> <br> <img src="/assets/Projects/WRO4.jpeg" height="330" width="290">  <img src="/assets/Projects/WRO5.jpeg" height="330" width="300"> <img src="/assets/Projects/WRO6.jpeg" height="330" width="290"> <br>

* ## **RFID Based Attendence System - 2017-18:** <br>
[College Project] Designed and Implemented automatic attendence marking and recording system using ESP32, MFRC522 transmitter, RFID tags and Google Sheets as database. <br>
Report: [RFID_Doc](https://docs.google.com/document/d/17jb2ki4bBRN9sly_19rZLRfEM30snpHmlIAO9eGujYA/edit?usp=sharing)

* ## **Male Female Classifier in Python:** <br>
A Male/Female face classifier using Artificial Neural Network built from scratch in python. <br>
Github Repo: [https://github.com/ankurbhatia24/Male-Female-Classifier](https://github.com/ankurbhatia24/Male-Female-Classifier) <br>
**MALE** <br>
<img src="/assets/Projects/MFClassifier1.png" height="64" width="64"> <img src="/assets/Projects/MFClassifier2.png" height="64" width="64"> <img src="/assets/Projects/MFClassifier3.png" height="64" width="64">  <img src="/assets/Projects/MFClassifier4.png" height="64" width="64"> <br>
**FEMALE** <br>
<img src="/assets/Projects/MFClassifier5.png" height="64" width="64">  <img src="/assets/Projects/MFClassifier6.png" height="64" width="64">  <img src="/assets/Projects/MFClassifier7.png" height="64" width="64">  <img src="/assets/Projects/MFClassifier8.png" height="64" width="64"> 

<!---2. [**Implementation of No Reference Image Quality Assessment using BRISQUE**](https://github.com/krshrimali/No-Reference-Image-Q
3. [**Template Matching, Cartoonification and more**]() (C++ and Python)
4. [**Deep Learning based Edge Detection**]() (Python)
5. **Flask based Web App using OpenCV** (Python)
6. [**Panorama Image Stitching using OpenCV**]() (Python and C++)  --->
 
<!---Blogs
====================
1. [**PyTorch C++ API: Using PyTorch C++ API using VGG-16 Network on MNIST Dataset**](https://ankurbhatia24.github.io/PyTorch-C++-API/)
2. [**Custom Data Loading using PyTorch C++ API**](https://ankurbhatia24.github.io/Custom-Data-Loading-Using-PyTorch-CPP-API/)
3. [**Training a Network on Custom Dataset using PyTorch C++ API**](https://ankurbhatia24.github.io/Training-Network-Using-Custom-Dataset-PyTorch-CPP/)
4. [**Classifying Dogs vs Cats using PyTorch C++ API: Part-1**](https://ankurbhatia24.github.io/Blog-Dogs-VS-Cats/)
5. [**Classifying Dogs vs Cats using PyTorch C++: Part 2**](https://ankurbhatia24.github.io/Classifying-Dogs-Cats-PyTorch-CPP-Part-2/)
6. [**Applying Transfer Learning on Dogs vs Cats Dataset (ResNet18) using PyTorch C++ API**](https://ankurbhatia24.github.io/Applying-Transfer-Learning-Dogs-Cats/)
7. [**What's so special about Gaussian Distribution?**](https://ankurbhatia24.github.io/Understanding-Gaussian-Distribution/)

Guest Blogs
====================
1. [**Convex Hull using Python and C++**](https://www.learnopencv.com/convex-hull-using-opencv-in-python-and-c/):

--->



