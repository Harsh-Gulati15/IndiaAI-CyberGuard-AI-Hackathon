# Crime Prediction Model

## Overview
This project uses machine learning to predict crime categories based on text descriptions and categorical data. The model combines TF-IDF vectorization with category encodings to achieve accurate predictions.

## Dataset
The dataset contains crime descriptions and their respective categories. The data has been cleaned and processed as part of the pipeline.

## Methodology
1. Data Cleaning and Preprocessing
   - Removed stopwords, punctuations, and performed text normalization.
2. Feature Engineering
   - Used TF-IDF for textual data.
   - Encoded categorical features using `LabelEncoder`.
3. Model Training
   - Trained a classifier on processed data (e.g., RandomForest, Logistic Regression).
4. Evaluation
   - Evaluated the model using metrics like accuracy, precision, recall, and F1-score.

Link to the.pkl file: https://drive.google.com/file/d/1mSUG-qfriAjm3B_VD087UUSm_hEGsv_R/view?usp=sharing
