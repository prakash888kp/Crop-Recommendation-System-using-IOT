SMART AGRICULTURE RECOMMENDATION SYSTEM TO IMPROVE THE PRODUCTIVITY OF CROPS

implemented IoT based real time data collection system to help the formers in leaf disease detection, crop recommendation and fertilizer recommendation.
• To develop a robust system that can diagnose plant diseases in remote places using techniques of machine learning and image processing.
• To suggest best crop for the farm, soil analysis is performed and machine learning technique is used to suggest best crop
• To suggest best fertilizer for the crop, soil analysis is performed and machine learning technique is used to suggest best fertilizer
• To make hassle free user experience introduced chat bot which can perform all the above actions with all languages using google API.



For creating weight file i used Ensemble learning link : https://github.com/prakash888kp/EnsembleDiseaseDetection/blob/main/Ensemble_Crop_Recommender_Final.ipynb

To Run the Project follow the below commands:

To run chatbot
rasa run --enable-api --cors "*"
rasa run actions

To run Django web module
python3 app.py

To capture photo on rpi
python3 cam.py
