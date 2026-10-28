# Personalized Music Recommendation Project
## Overview
This school project explores machine learning and personalized music recommendations using Python. It examines music listening behavior and song characteristics to explore how user preferences can be predicted.
## Project Objectives
* Explore and prepare a music listening dataset.
* Apply data preprocessing and encode categorical variables.
* Build a Random Forest Classification model.
* Evaluate model performance.
* Explore class imbalance and recommendation logic.
## Tools and Technologies
* Python
* Jupyter Notebook
* pandas and NumPy
* scikit-learn
* Random Forest classification
## Dataset
  The project uses a dataset containing user information, song characteristics, and listening behavior. Variables explored include artist, genre, danceability, energy, tempo, valence, play count, repeat count, and a preference label.
  The data set is not included in this repository. Anyone wishing to reproduce the analysis will need access to the original dataset.
## Methodology
   1. Load and explore the dataset.
   2. Prepare data and encode categorical variables.
   3. Select features for classification.
   4. Train a Random Forest model.
   5. Evaluate predictions and examine class imbalance.
   6. Explore logic for generating personalized song recommendations.
## Results and Observations
The initial model reported approximately 70.1% accuracy. 
However the classification results showed that performance differed between the target classes, highlighting limitations that accuracy alone does not capture.
The notebook also explores personalizied recommendations. 
In one example, the recommendation process returned two songs for a user who had already interacted with most of the songs considered.
## Limitations and Future Improvements
* Improve evaluation of performance across both target classes.
* Investigate methods for handling class imbalance.
* Compare additional machine learning models.
* Evaluate recommendations using metrics designed for recommendation systems.
## Project File
Final project code.ipynb contains the original project notebook, including the analysis and model implementation.
## Skills Demonstrated
This project demonstrates hands-on academic experience with Python, data preprocessing, machine learning classification, model evaluation, and recommendation logic.
           
