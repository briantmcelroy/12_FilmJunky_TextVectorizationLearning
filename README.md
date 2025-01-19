# 12_FilmJunky_TextVectorizationLearning

## About this Project

The hypothetical Film Junky Union, a self-proclaimed edgy community for classic movie enthusiasts, is developing a system for filtering and categorizing movie reviews. The goal is to train a model to automatically detect negative reviews by receiving raw text as input. We have been provided a dataset of IMBD movie reviews with polarity labelling to build a model for classifying positive and negative reviews.

Textual processing has developed rapidly over the last few decades, and this project is a foundational demonstration of single-target lemmatization and text analysis. It shows how lemmas can predict target feature values via standard machine learning models.

## Running it Yourself

The Jupyter notebook is self-contained and reflects the outputs of the code contained within. If you would like to connect to your own environment and run the notebook, or make changes on your own fork of the repo, you may do so after cloning. Make sure the environment is either based in the upper-level folder to which you clone the repo, or be sure to replace the dataset file references with a direct local reference to the /datasets/ folder on your machine. 

The project relies on multiple dependencies. Our scikit-learn version is 1.5.1. Our spacy version is 3.8.2, and the en_core_web_sm version that spacy pulls from is 3.8.0. The lightgbm version is 4.5.0. The nltk version is 3.9.1. The seaborn version was 0.13.2. Finally, our tqdm version was 4.67.1. The project is stable with Python 3.11.