Music Genre Classification with PCA
Overview
This project implements a music genre classification pipeline using Principal Component Analysis (PCA) and logistic regression. It analyzes a dataset of 1,000 music tracks, each described by various audio features (such as tempo, dynamic range, instrumental detection, etc.), and predicts their genre.

Objectives
Explore and visualize audio features from a music dataset
Preprocess data to handle null values and encode target labels
Analyze and visualize the distribution of music genres
Apply dimensionality reduction with PCA
Build and evaluate a logistic regression classifier to predict genres
Dataset
File: music_dataset_mod.csv
Description: Each row represents a track with features like Tempo, Dynamics Range, Vocal Presence, Percussion Strength, etc., and a genre label.
Legend: Feature descriptions are in Music Data Legend.xlsx.
Approach
Data Loading: Imported CSV using pandas.
Exploration: Analyzed null values, statistical summaries, and genre balance.
Visualization: Visualized genre distribution with Seaborn.
Preprocessing: Label encoding, train/test split, and standardization.
Dimensionality Reduction: Applied PCA to reduce feature space.
Classification: Trained logistic regression model and evaluated on test set.
Results: Achieved (insert your accuracy here)% accuracy; genre data appeared (balanced/imbalanced); main insights.
Results
Model accuracy: X% (replace with your result)
Most influential features were identified using PCA
Genre distribution was (balanced/imbalanced) — discuss any challenges
How to Run
Upload the notebook (.ipynb) and dataset to Google Colab or run locally with Jupyter.
Install dependencies:
pip install pandas numpy scikit-learn matplotlib seaborn
Run each cell in order.
Requirements
Python 3.x
pandas
numpy
scikit-learn
matplotlib
seaborn
Project Structure
Music Genre Classification with PCA.ipynb — Main Jupyter Notebook
music_dataset_mod.csv — Dataset
Music Data Legend.xlsx (optional) — Feature descriptions
