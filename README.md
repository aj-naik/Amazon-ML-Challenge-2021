# Amazon-ML-Challenge-2021

Amazon Machine Learning Challenge is a competition for all
engineering students, researchers to showcase their talent
and find creative and innovative solutions to real world
problems. The dataset provided by Amazon had 3 million
rows and the challenge was to use that data and come up
with an efficient model to classify products into
different nodes. This is our solution to Amazon ML
Challenge 2021 which fetched us a rank 30 briefly on the
first submission itself.

# Dataset:-
Dataset was provided by Amazon and was a csv file containing more than 3 million rows of raw data

# Data Preparation:-
- Cleaning the data by removing all links, patterns, emojis etc.
- Creating new features using 'Title', 'Bullet Points'.
- Shuffling the data to get better sampling.
- Taking subset of each class for training

# Modelling:-
We started with classical ML algorithms which served us well and then moved on to other algorithms and models. 

Classical models we tried:
- KNN
- Random Forest
- SVM
- Naive Bayes

Out of these KNN gave the best output

Deep learning based models we tried:-
- Tried a Conv1d based architecture we created ourselves.
- Deep Neural Network
- BERT transformer.
