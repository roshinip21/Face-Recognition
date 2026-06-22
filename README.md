## Face-Recognition
An Image recognition and detection application built with Python, OpenCV, Haar Cascade model and PostgreSQL pgvector

## Description
This project was developed by Roshini Padmanabha and team as a Final Project for MIS-695 (Business System Design and Analysis). It is a full-stack face recognition pipeline that ingests group photos, extracts individual face embeddings using deep learning, stores them in a vector database, and retrieves the closest matches via cosine similarity search.

## Tech Stack

| Layer | Technology |
|---|---|
| Language | Python 3.8+ |
| Face Detection | OpenCV + Haar Cascade |
| Embeddings | OpenAI CLIP |
| Database | PostgreSQL + pgvector |
| Environment | Google Colab |

## Installation
1.\tUse Google Colab as the development environment.
2.\tInstall the necessary libraries: 
o\tOpenCV
o\tPostgreSQL and pgvector extension
o\tTensorFlow or any required libraries for deep learning
3.\tLoad the Haar Cascade file and set up a PostgreSQL database for embedding storage.
 
## Inputs
This project takes the following inputs:
1.\tGroup Image: An image containing multiple people for face detection and cropping.
2.\tIndividual Image: A single image used for similarity matching against the database.
 
## Outputs
The project generates the following outputs:
•\tFace Detection Results: Individual faces detected and cropped from group pictures.
•\tEmbedding Generation: Numeric embeddings for each detected face.
•\tDatabase Storage Confirmation: Status updates for successfully stored embeddings.
•\tSimilarity Retrieval: Closest matches for the uploaded face image based on embeddings.
•\tSimilarity Scores: Ranked list of matches with similarity percentages.
•\tMatching Visualization: Retrieved images matching the input face, highlighting recognized identities.
•\tProcessing Time Summary: Metrics showing average time for detection, embedding generation, and matching.
•\tMatch Status Log: Log of successful and failed detection and match attempts.
 
## Main Code File
The main code file for this project is Code.ipynb, which contains the core logic for detection, embedding generation, and similarity matching. Additionally, the code file FaceDetection.ipynb is used for implementing the Haar Cascade model face detection.
 
## Running the Code
1.\tOpen the Code.ipynb file in Google Colab.
2.\tExecute the cells line by line to: 
o\tUpload images.
o\tDetect faces and create embeddings.
o\tStore embeddings in the database.
o\tPerform similarity matching for uploaded images.
3.\tReview the outputs in the Colab notebook, including visualizations and logs.
 
## Deployment

This project runs in a Google Colab Notebook. To execute:
1.\tUpload the Colab notebook and required files to your Google Drive.
2.\tOpen the notebook in Google Colab and run the code as described in the Running the Code section.
