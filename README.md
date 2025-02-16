<<<<<<< HEAD
# suicidal-ideation
=======
# suicidal-ideation
Deep learning Approaches for the detection of Suicidal Tendencies on Social Media:

This project aims to develop a model which can detect suicidal ideations on social media using Natural Language Processing(NLP) and Machine Learning (ML) Models including BiLSTM(Bidirectioal Long Short term Memory)+ Word embedding + Convolutional Neural networks(CNN). The model helps in early detection, raising awareness, and contributing to suicide prevention efforts. Ultimately, this framework can play a crucial role in creating a safer online environment and supporting mental health initiatives. 

Dataset:

The Dataset being used to train this model is a collection of posts from the "SuicideWatch" and "depression" subreddits of the Reddit platform.The posts are collected using Pushshift API. All posts that were made to "SuicideWatch" from Dec 16, 2008(creation) till Jan 2, 2021, were collected while "depression" posts were collected from Jan 1, 2009, to Jan 2, 2021.

Data Preprocessing:

At this stage , all the messages are converted to lower case, filtering the text by removing the symbols,emojis,numbers,special characters,and any other than Alphabets. Removal of Stopwords is carried by nltk package . Stemming of the words in message is done where the words get converted to their root form.

Feature Extraction:

Dataset is Split into Train and Test as 70% and 80% respectively.Tokenizer() function is carried out. Padding is done to equalize the length of the sequence of each line. hi
>>>>>>> 51d3df0 (initial commit)
