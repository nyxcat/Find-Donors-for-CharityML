# Find-Donors-for-CharityML


### Introduction
This project employs several supervised algorithms to accurately model individuals' income using data collected from the 1994 U.S. Census. The goal with this implementation is to construct a model that accurately predicts whether an individual makes more than $50,000. The best candidate algorithm is random forest classifier, which yields highest F-socre on the testing set time efficienctly. 
The dataset for this project originates from the UCI Machine Learning Repository. The datset was donated by Ron Kohavi and Barry Becker, after being published in the article "Scaling Up the Accuracy of Naive-Bayes Classifiers: A Decision-Tree Hybrid". You can find the article by Ron Kohavi online. The data we investigate here consists of small changes to the original dataset, such as removing the 'fnlwgt' feature and records with missing or ill-formatted entries.
There are 2 datasets used in this project:
- messages.csv, containing real messages that were sent during disaster events
- categories.csv, containing multi-class output of each message
The project  includes a web app where an emergency worker can input a new message and get classification results in several categories. The web app will also display visualizations of the data. 

### Data Processing 
1. 

### Requirement
json
plotly
pandas
numpy
skmultilearn
nltk (punkt, stopwords, wordnet, averaged_perceptron_tagger)
flash
sqlalchemy
sqlite3

