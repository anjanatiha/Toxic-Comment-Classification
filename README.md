'''
*****************************************************************************************************************************************
Classify comments on categories - 
toxic, severe_toxic, obscene, threat, insult, identity_hate, any, none
*****************************************************************************************************************************************
*****************************************************************************************************************************************
Procedure:
*****************************************************************************************************************************************
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
*****************************************************************************************************************************************
*****************************************************************************************************************************************

'''
