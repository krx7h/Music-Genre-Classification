📘 Project Overview
This project focuses on classifying music tracks into their respective genres using a supervised machine learning pipeline. The model is trained on audio-related features such as tempo, danceability, loudness, and more, using the LightGBM classifier.

🔧 Key Features
Cleaned and preprocessed real-world music metadata

One-hot encoding of categorical features (key, mode)

Removal of low-quality genre classes to boost model precision

Stratified train/validation/test split for balanced evaluation

Missing value imputation using SimpleImputer

Training with LightGBMClassifier

Evaluation using accuracy and detailed classification reports

🗂 Dataset
Source: music_genre.csv

Contains features like tempo, energy, loudness, danceability, etc.

Target: music_genre (multiclass classification)

📊 Model Performance
Evaluated on both validation and test sets:

Accuracy Score

Classification Report (Precision, Recall, F1-score per genre)

