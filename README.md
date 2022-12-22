# NLP_Mini_Projects

This repository various small scale projects based on Natural Language Processing.  
Some of the most significant ones are 
> 1. Part of Speech Tagger 
> 2. Password Strength Classifier
> 3. Topic Modeling using Non-negative Matrix Factorization  

## Part of Speech Tagger
We incorporate context of a word in our model to assign it a Part of Speech  
Eg. The word **plant** may be a verb or a noun depending on the context
> Let's **plant** a tree. --> plant is a Verb here  
> Photosynthesis is a transfer of energy from the Sun to a **plant**. --> plant is a Noun here

## Password Strength Classifier
>It is a supervised learning based model which can be used to classify a password as a strong, weak or medium  
>Used Tfidf Vectorizer from sklearn and a Tokenizer which splits a password in its constituent characters  
>Got 98.63% accuracy on test data and 99.10% accuracy on training data using XGBClassifier from XGBoost  

## Topic Modeling
Topic Modeling is an unsupervised learning algorithm which enables one club a group of articles, books, tweets etc into different topics to which they belong. For eg. Politics, Wellbeing, Sports, Cinema, Culture, Climate, etc
