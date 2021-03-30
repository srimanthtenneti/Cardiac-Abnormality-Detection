# Diagnostico



## Table of Contents
1. Introduction
2. Inspiration behind the product
3. Working

### 1. Introduction

Using simple Machine Learning , Statistical Modelling we plan to make diagnosis smoother and faster for both patients and medical personnel. 

### 2. Inspiration behind the product

In early 2020 when the first wave of COVID-19 hit the place where I live (Hyderabad) medical students and nurses were put on the front line. In government hospitals there is a lack of medical personnel, so, to attend to the extreme large volume of incoming patients medical students were being used to monitor and administer medicines to the patients. These people were not given proper protective measures and were getting exposed to an unknown virus at that time.  Many of my friends studying medicine were there in the front line and listening to their story inspired me to come up with a method to diagnose and monitor the patients remotely and from the past one year I have been working on similar lines to help them.
 
### 3. Working

Our solution finds its application on two major fronts. One is the hospital front where we designed a low power , low cost , sterializable IOT based wearable device that would collect elementary body parameters like temperature, heart rate, SPO2(an indicator of COVID-19) & ECG data. This data is then pushed to a cloud platform where this data would be stored for future use. When the doctor wants to know the condition of  a patient then he simply has to enter the patient ID and the entire patient data would be available for him to monitor. Also, we have designed a serum cholesterol predictor that uses Machine Learning to determine the cholesterol levels instead of traditional painful invasive methods that rely on collecting blood samples. 

Also, a recent addition to our hospital end software is a CT , X-ray classifier that can classify the scans based on the body part and categorize them into folders. When a scan enters the model it uses Convolutional Neural Networks to classify them into chest, breast, head & abdomen and categorizes them. This helps in automation of classifying the scans by removing the need of the medical personnel physically doing this task. As many of the CT and X-ray machines have NVIDIA based GPUs integrated in them, using the NVIDIA-ClaraSDK would help us integrate our solution directly with the existing hardware removing the need for new hardware. 

The second front where our product finds its application is with the common man. We would make a version of this available for the public where the user would be able to find out his or her 
