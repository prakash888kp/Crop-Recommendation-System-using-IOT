# Smart Agriculture Recommendation System 🌾

## Table of Contents
- [Overview](#overview)
- [Features](#features)
- [Hardware Requirements](#hardware-requirements)
- [Software Requirements](#software-requirements)
- [Flow of the Project](#flow-of-the-project)
- [Data Collection](#data-collection)
- [Usage](#usage)
- [Selected For](#selected-for)

## Overview
1. **Leaf Disease Detection**: Utilizes machine learning and image processing techniques for diagnosing plant diseases.
2. **Crop Recommendation**: Suggests the best crop based on soil analysis.
3. **Fertilizer Recommendation**: Recommends the optimal fertilizer for crops through soil analysis.
4. **Chatbot for Farmers**: Hassle-free user experience in multiple languages using Google API.

## Features
- Real-time data collection through IoT.
- Diagnosis of plant diseases even in remote locations.
- Soil analysis for crop and fertilizer recommendation.
- Multilingual chatbot for easy interaction.

## Hardware Requirements
- Raspberry Pi
- ESP8266
- Soil & Moisture Sensor
- Temperature Sensor (DHT 11)
- pH Sensor
- Pi Cam

## Software Requirements
- Raspbian OS
- VS Code
- Django
- Flask
- Firebase
- Rasa Framework
- Python

## Flow of the Project
- Overview 1
  ![Overview 1.1](https://github.com/prakash888kp/Crop-Recommendation-System-using-IOT/blob/main/images/overview.png)
  
- Overview 2
  ![Overview 1.2](https://github.com/prakash888kp/Crop-Recommendation-System-using-IOT/blob/main/images/overview2.png)


## Data Collection
- Utilized a public dataset containing data for 22 crops including NPK levels, temperature, humidity, moisture, and rainfall.
- Total dataset consists of 53K images including 30 diseases across various crops.
- Dataset divided into an 80/20 ratio for training and validation sets.

## LEAF DISEASE DETECTION 
![DEMO 1.1](https://github.com/prakash888kp/Crop-Recommendation-System-using-IOT/blob/main/images/demo%201.1.png)
![DEMO 1.2](https://github.com/prakash888kp/Crop-Recommendation-System-using-IOT/blob/main/images/demo1.2.png)
![DEMO 1.3](https://github.com/prakash888kp/Crop-Recommendation-System-using-IOT/blob/main/images/demo1.3.png)

## CROP RECOMMENDATION 
![DEMO 2.1](https://github.com/prakash888kp/Crop-Recommendation-System-using-IOT/blob/main/images/demo2.1.png)
![DEMO 2.2](https://github.com/prakash888kp/Crop-Recommendation-System-using-IOT/blob/main/images/demo2.2.png)
![DEMO 2.3](https://github.com/prakash888kp/Crop-Recommendation-System-using-IOT/blob/main/images/demo2.3.png)
![DEMO 2.4](https://github.com/prakash888kp/Crop-Recommendation-System-using-IOT/blob/main/images/demo2.4.png)
![DEMO 2.5](https://github.com/prakash888kp/Crop-Recommendation-System-using-IOT/blob/main/images/Screenshot%202023-09-12%20at%202.22.17%20PM.png)

## FERTILIZER RECOMMENDATION
![DEMO 3.1](https://github.com/prakash888kp/Crop-Recommendation-System-using-IOT/blob/main/images/demo3.1.png)
![DEMO 3.2](https://github.com/prakash888kp/Crop-Recommendation-System-using-IOT/blob/main/images/demo3.2.png)
![DEMO 3.3](https://github.com/prakash888kp/Crop-Recommendation-System-using-IOT/blob/main/images/demo3.3.png)
![DEMO 3.4](https://github.com/prakash888kp/Crop-Recommendation-System-using-IOT/blob/main/images/Screenshot%202023-09-12%20at%202.24.55%20PM.png)

## CHATBOT IMPLEMETATION FOR FARMERS
![Chatbot](https://github.com/prakash888kp/Crop-Recommendation-System-using-IOT/blob/main/images/demo4.png)

## Model Accuracy

![Result](https://github.com/prakash888kp/Crop-Recommendation-System-using-IOT/blob/main/images/result.png)

## Usage

### Running the chatbot

> rasa run --enable-api --cors "*"

> rasa run actions

### Running the Django web module

> python3 app.py

### Capturing photo on Raspberry Pi

> python3 cam.py

## Selected For

- This Project is selected for TNSCST

