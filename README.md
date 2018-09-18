'''
********************************************************************************************************************************************************************************************************************************************************************************
Title: Classify comments on categories - "Toxic", "Severe Toxic", "Obscene", "Threat", "Insult", "Identity Hate", "Any of the Above", "None of the Above".
****************************************************************************************************************************************
****************************************************************************************************************************************
****************************************************************************************************************************************
Project Description:
- Classify around 130, 000 text comments of size 34MB on categories - "Toxic", "Severe Toxic", "Obscene", "Threat", "Insult", "Identity Hate", "Any of the Above", "None of the Above"
- Used features fro AAAI 2018 paper "Anatomy of Online Hate: Developing a Taxonomy and Machine Learning Models for Identifying and Classifying Hate in Online News Media" by "Salminen, Almerekhi". 
- Built pipelines for machine learning model training for reading file, creating training testing dataset, preprocessing, extracting features, and training and evaluation in grid search approach for multiple models.
****************************************************************************************************************************************
****************************************************************************************************************************************
Procedure:
****************************************************************************************************************************************
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
****************************************************************************************************************************************
****************************************************************************************************************************************
'''
