# Model-for-detecting-movie-reviews-for-IMDB-website-for-Filmy-Junk-Union-_Sprint_14
Model for detecting movie reviews for IMDB website for Filmy Junk Union 

The Film Junky Union: Automated Movie Review Classification
Project Overview
The Film Junky Union, an edgy community for classic movie enthusiasts, is developing a system for filtering and categorizing movie reviews. The goal is to train a machine learning model to automatically detect negative reviews, helping viewers decide which movies to watch without wasting time.
Using a dataset of IMDb movie reviews with polarity labeling, the system classifies reviews as positive or negative, ensuring an F1 score of at least 0.85 for high accuracy.
Data Preprocessing
To prepare the dataset:
- Removed punctuations and white spaces for consistency.
- Converted text to lowercase to minimize confusion with uppercase variations.

Models Tested
Several models were trained and evaluated for performance:
- Dummy Classifier (Baseline Model)
- Logistic Regression
- Multinomial Naïve Bayes
- LightGBM Classifier

Model Performance
    Logistic Regression  F1 Score 0.88
    LightGBM Classifier  F1 Score 0.86
             Others      F1 Score <0.85
Logistic Regression performed best, achieving an F1 score of 0.88. Since this is a binary classification task, where reviews are labeled as:
- 0 → Negative
- 1 → Positive
Logistic Regression excelled due to the moderate-sized dataset, making it an ideal choice for reliable predictions.

Limitations
- Logistic Regression works well with moderate datasets but may struggle with very large or very small datasets.
- Classifying highly subjective reviews can still be a challenge.

Deployment
The trained model performs effectively on new review datasets and is ready for real-world applications.

Use BLANK_README.md to get started Build With: This is the list of the libraries used by me to run this project were pandas,numpy, matplotlib.pyplot, plotly.express and stats.

Getting Started: This is an example of how you may give instructions on setting up your project locally. To get a local copy up and running follow these simple steps. Prequisites: This is an example of software and how to install them. VS Code

Clone the repo:https://github.com/sohini8328/Model-for-detecting-movie-reviews-for-IMDB-website-for-Filmy-Junk-Union-_Sprint_14.git
