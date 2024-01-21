# Leaf-Disease-Classification-With-Web-App-Deployment

# Overview 

The Leaf Disease Classification model is a machine learning solution designed 
to identify and classify diseases in plant leaves based on images. The system is 
implemented using Python, leveraging machine learning techniques, and is 
complemented by a Flask server to provide a seamless and user-friendly 
experience.

# Key Components:

# 1. Machine Learning Model:
The core of the system is a robust machine learning model trained to recognize 
various diseases affecting plant leaves. The model is trained on a diverse 
dataset containing images of healthy leaves and leaves affected by different 
diseases. Utilizing popular machine learning libraries in Python, such as scikitlearn or TensorFlow, the model learns to extract relevant features and patterns 
to make accurate predictions.

# 2. Flask Server:

To make the model accessible to users, a Flask server is employed. Flask is a 
lightweight web framework in Python that allows for the creation of RESTful 
APIs. The Flask server serves as the bridge between the machine learning 
model and the user interface, handling incoming requests and providing 
predictions.

# 3. User Interface:
The user interacts with the system through a user-friendly interface, where 
they can upload an image of a plant leaf. The image is then sent to the Flask 
server, which, in turn, forwards it to the machine learning model for 
classification. The result, indicating the presence or absence of disease and the 
specific type of disease if detected, is then presented to the user.

# Workflow:

# Image Upload:
Users upload an image of a plant leaf through the app's interface.
# Flask Server Interaction:
The Flask server receives the image and passes it to the machine learning 
model for classification.
# Machine Learning Classification:
The machine learning model processes the image and classifies the leaf as 
healthy or identifies the specific disease if present.
# Result Presentation:
The classification result is sent back to the user interface via the Flask server.
# User Feedback:
The user receives feedback on the leaf's health status, enabling prompt action 
in case of disease presence.

# Flask Server Deployment 

![Leaf1](https://github.com/KAVINT21/Leaf-Disease-Classification-With-Web-App-Deployment/assets/95117554/d34ae1dc-ca79-47fb-a5c5-fedb39879cde)

![Test_Leaf_Image_used](https://github.com/KAVINT21/Leaf-Disease-Classification-With-Web-App-Deployment/assets/95117554/7b27b879-5b76-403d-83bc-d6681ba8e36c)

