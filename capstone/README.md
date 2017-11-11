# Using Supervised Learning to Predict Myers-Briggs Personality Types from Text

This is the capstone project I completed as part of the Udacity Machine Learning Nanodegree. In this project, machine learning methods are being used to analyze posts of users in the *personality cafe* forum. These users have each been labelled with one of the 16 Myers-Briggs personality types. The classifiers developed in this project achieve different accuracy scores in the four different dimensions of personality (I/E: 64.2%; N/S: 67.5%; T/F: 74.0%; J/P: 61.1%). For a complete description of this project, please read the file *report.pdf*. The source code for analyzing the data and for training the classifiers is contained in *Myers-Briggs.ipynb*.

Data needed to run this project:

 - Labelled users and their forum posts (https://www.kaggle.com/datasnaek/mbti-type)
 - Google's pretrained word2vec vectors (https://drive.google.com/file/d/0B7XkCwpI5KDYNlNUTTlSS21pQmM/edit)

Necessary Python libraries
- Scikit-Learn
- Gensim
- NLTK
- Seaborn
- Pandas
- Pyplot
- Spacy
