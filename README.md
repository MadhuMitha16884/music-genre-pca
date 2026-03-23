Music Genre Classification with PCA

Overview

This project uses machine learning to classify music tracks into genres based on their audio features. Principal Component Analysis (PCA) is employed for dimensionality reduction, paired with a logistic regression classifier.

Objectives

Explore and visualize a music dataset containing 1,000 tracks
Analyze feature distribution and handle missing values
Perform genre distribution analysis and address any imbalance
Preprocess data and reduce dimensionality with PCA
Build and evaluate a logistic regression classification model

Dataset

File: music_dataset_mod.csv
Features: Tempo, Dynamics Range, Vocal Presence, Percussion Strength, String Instrument Detection, Electronic Element Presence, Rhythm Complexity, Drums Influence, Distorted Guitar, Metal Frequencies, Ambient Sound Influence, Instrumental Overlaps, Genre (target)
Feature Legend: See Music Data Legend.xlsx for detailed info

Approach

Data Loading & Exploration: Used pandas for initial data loading and inspection.
Data Visualization: Plotted genre distribution with Seaborn's countplot to assess balance.
Preprocessing: Label-encoded genres, handled missing values, train-test split, and standardized features.
PCA: Reduced feature space for model efficiency and visualization.
Modeling: Applied logistic regression on PCA-transformed data.
Evaluation: Calculated accuracy and generated a classification report.

Results

Model Accuracy: (Update this with your actual result, e.g., 86% on test set)
Observations: (Note if genre distribution was balanced, if PCA improved performance, any interesting findings about feature importance, etc.)

How to Run

Clone this repo and upload all files to Google Colab or run locally with Jupyter.
Install dependencies (if running locally):
pip install pandas numpy scikit-learn matplotlib seaborn
Open the Jupyter Notebook and run cells in order.

File Structure

Music Genre Classification with PCA - Project.ipynb — Main code and analysis
music_dataset_mod.csv — Music tracks dataset
Music Data Legend.xlsx — Column/feature descriptions

Requirements

Python 3.x
pandas
numpy
scikit-learn
matplotlib
seaborn



Update the Model Accuracy and Observations sections once you run your final notebook and have your results.
If you want a badge, image, or want to further polish the README, just let me know! Great jo
