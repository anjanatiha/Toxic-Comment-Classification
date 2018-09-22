# Toxic Comment Classification

#### Technology : Python, Machine Learning
#### Duration   : Aug - Sep 18

### Description
1. Classified around 130, 000 text comments of size 34 MB on categories - "Toxic", "Severe Toxic", "Obscene", "Threat", "Insult", "Identity Hate", "Any of the Above", "None of the Above".
2. Used 17 features from AAAI 2018 paper "Anatomy of Online Hate: Developing a Taxonomy and Machine Learning Models for Identifying and Classifying Hate in Online News Media" by "Salminen, Almerekhi". 
3. Built pipelines for machine learning model training for reading file, creating training testing dataset, preprocessing, extracting features, and training and evaluation in grid search approach for multiple models.
4. Generated aggregated report and visualization on different machine learning model performance.


### Procedure:

1. Build pipelines for machine learning model training for reading file, creating training testing dataset, preprocessing 
   (cleaning text, tokenization, single character count, url count, modal count, non alpha mid character), 
   extracting features, and training and evaluation in grid search approach for mutiple models.
2. Preprocessing unit replaced non standard input features with default value.
3. Build feature class for following features: 
    - Count of exclamations, periods, question marks, punctuation, special characters, repeated punctuation, and quotes 
      in each comment.
    - Count of single-char. tokens in each comment.
    - Count of URLs in each comment.
    - Length of the comment (in chars. and in tokens).
    - Total number of capital letters in the tokens.
    - Total number of emoticons in each comment.
    - Total number of modal words in each comment.
    - The modal words that were used are: can, could, may, might, must, will, would, and should.
    - Total number of tokens with non-alphabetic characters in the middle.
4. Build model training pipeline for both classification and regression
5. Generate agregated report on performance for various models.
6. Visualization for different model performance.


#### Tools Requirement: Anaconda, Python 

Current Version  : v1.0.0.0

Last Update      : 09.21.2018
