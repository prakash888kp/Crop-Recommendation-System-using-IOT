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
- Overview 2

## Data Collection
- Utilized a public dataset containing data for 22 crops including NPK levels, temperature, humidity, moisture, and rainfall.
- Total dataset consists of 53K images including 30 diseases across various crops.
- Dataset divided into an 80/20 ratio for training and validation sets.

## Usage

### Running the chatbot

rasa run --enable-api --cors "*"

rasa run actions

### Running the Django web module

python3 app.py

### Capturing photo on Raspberry Pi

python3 cam.py

## Selected For

- This Project is selected for TNSCST

