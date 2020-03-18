# TedEx Talks: Topic Modeling and Analysis
TedEx Data is being downloaded from Kaggle which contains the information about 2467 ted talks happened between 2007 and 2014. The dataset contains complete "Transcript" of the talk, "Number of Comments" it grossed on the discussion forums, "Released Date" the date it was released, "Number of Views", and the information about the Author and Topic of each talk.

# Description:
# Data:
For this code to work you would need to download the TedEx Talks Dataset from Kaggle. Link has been provided below.
https://www.kaggle.com/rounakbanik/ted-talks
# FrameWork:
I have used Gensim Doc2Vec model, also i have used Spherical Clustering algorithm for Clustering the data. Then i have used Pandas, Seaborn, Matplotlib and Sklearn for my analysis. All the libraries needed for the code to run are being provided at each step in the code.
# Motivation and Tasks:
Task 1: Motivation for this project is to find the general topics (Genres) for different type of talks such that we can cluster 2467 talks in a few topics, e.g if we have 6 talks where the theme was "Personal Growth and Motivation", all of them should be clustered in the topic "Personal Growth and Motivation". This is an unsupervised learning problem where we have the transcript for 2467 talks and we have to generate let's say 10-15 topics that represent all these 2467 talks.

Task 2: With the topics identified it would be interesting to know that what kind of topics gross most comments on discussion forums and what kind of topic gets viewed the most, do they have a correlation between comments and views grossed by a talk. Also, we are given the date the Talk was arranged, so we can also learn how the trend in the popularity of each topic has changed over the years. e.g maybe in 2007 talks related to "Science and Innovation" were famous while in 2016 the talks related to "Politics and Economic Issues" were famous.
