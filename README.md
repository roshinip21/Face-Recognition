## Face-Recognition
An Image recognition an detection application built with Python, OpenCV, Haar Cascade model and PostgreSQL pgvector


## Description
This project was created by Roshini Padmanabha and her team as the Final Project for the MIS-695 Business System Design and Analysis class. The application allows users to upload images, detects faces using Deep Learning models from OpenCV, and retrieves potential matches from a database by comparing embeddings.
 
## Installation
1.	Use Google Colab as the development environment.
2.	Install the necessary libraries: 
o	OpenCV
o	PostgreSQL and pgvector extension
o	TensorFlow or any required libraries for deep learning
3.	Load the Haar Cascade file and set up a PostgreSQL database for embedding storage.
 
## Inputs
This project takes the following inputs:
1.	Group Image: An image containing multiple people for face detection and cropping.
2.	Individual Image: A single image used for similarity matching against the database.
 
## Outputs
The project generates the following outputs:
•	Face Detection Results: Individual faces detected and cropped from group pictures.
•	Embedding Generation: Numeric embeddings for each detected face.
•	Database Storage Confirmation: Status updates for successfully stored embeddings.
•	Similarity Retrieval: Closest matches for the uploaded face image based on embeddings.
•	Similarity Scores: Ranked list of matches with similarity percentages.
•	Matching Visualization: Retrieved images matching the input face, highlighting recognized identities.
•	Processing Time Summary: Metrics showing average time for detection, embedding generation, and matching.
•	Match Status Log: Log of successful and failed detection and match attempts.
 
## Main Code File
The main code file for this project is Code.ipynb, which contains the core logic for detection, embedding generation, and similarity matching. Additionally, the code file FaceDetection.ipynb is used for implementing the Haar Cascade model face detection.
 
## Running the Code
1.	Open the Code.ipynb file in Google Colab.
2.	Execute the cells line by line to: 
o	Upload images.
o	Detect faces and create embeddings.
o	Store embeddings in the database.
o	Perform similarity matching for uploaded images.
3.	Review the outputs in the Colab notebook, including visualizations and logs.
 
#Deployment
This project runs in a Google Colab Notebook. To execute:
1.	Upload the Colab notebook and required files to your Google Drive.
2.	Open the notebook in Google Colab and run the code as described in the Running the Code section.
![image](https://github.com/user-attachments/assets/7a5eee80-4680-424d-af23-993eaa80458d)
