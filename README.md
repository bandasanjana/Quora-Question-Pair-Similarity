# Quora-Question-Pair-Similarity
Problem Statement:
Identify which questions asked on Quora are duplicates of questions that have already been asked.
This could be useful to instantly provide answers to questions that have already been answered.
We are tasked with predicting whether a pair of questions are duplicates or not.

 Objectives and Constraints
The cost of a mis-classification can be very high.
You would want a probability of a pair of questions to be duplicates so that you can choose any threshold of choice.
No strict latency concerns.
Interpretability is partially important.

Data Overview 
Data will be in a file Train.csv ,
Train.csv contains 5 columns : qid1, qid2, question1, question2, is_duplicate 
Size of Train.csv - 60MB ,
Number of rows in Train.csv = 404,29

Type of Machine Leaning Problem
It is a binary classification problem, for a given pair of questions we need to predict if they are duplicate or not.

Performance Metric 
log-loss,
Binary Confusion Matrix
