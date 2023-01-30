# Book-Recommender

A Machine Learning Project that makes the use of KNN and similarity_cosines to recommend books to the users.Used Collaborative filtering technique to recommend Books to the users

# File Folder

1.Book Recommendation - Contains the actual Recommender System.
2.Datsets

# Tools Used

pandas,numpy
 
# Objective of the Project

The objective of this Recommender system was to Recommend Books to the user who has some sort of similarity with other users 


# Steps involved in making the Recommender System

1.We start off by importing and taking a look at our data.We have in total 3 diff. csv files

2.We then check some basic information such as checkig for any null data present ,data type of the each column.This step helps us in knowing a little bit more about our data and makes our further processes easier.

3.We exclude top 200 books based on book ratings.

4.We feed these pivot table to our model which is a KNN based model. So what it does is, a user inputs a name of the book, this book name becomes a data point, then our model looks for other data points that are in the vicinity of this data point to make our Recommendation.

5.We also make a system using Cosine_similarity which also recommend books which are closer to that point.

#Results
The System actually makes some decent recommendations based on the inputs.
