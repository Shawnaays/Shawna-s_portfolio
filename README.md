
READ.ME
Introduction :
Nowadays with so many books available, it can be hard to select the best ones to read. The dataset provided is a curation of Goodreads books based on real user information. It can be used for many tasks like predicting a book’s rating.

Objective :
The main objective is to create a machine learning project to recommend relevant books based on ratings.


Data Summary :
1.	bookID: A unique identification number for each book.
2.	title: The name under which the book was published.
3.	authors: The names of the authors of the book. Multiple authors are delimited by “/”.
4.	average_rating: The average rating of the book received in total.
5.	isbn: Another unique number to identify the book, known as the International Standard Book Number.
6.	isbn13: A 13-digit ISBN to identify the book, instead of the standard 11-digit ISBN.
7.	language_code: Indicates the primary language of the book. For instance, “eng” is standard for English.
8.	num_pages: The number of pages the book contains.
9.	ratings_count: The total number of ratings the book received.
10.	text_reviews_count: The total number of written text reviews the book received.
11.	publication_date: The date the book was published.
12.	publisher: The name of the book publisher.

Problem :
How to evaluate the ratings of a book ?

Problem Statement :
Which Machine Learnin algo is the best performing in the book rating prediction ?
Predict the rating of a book is a perfect way to use linear regressions in python.
Steps in this project :
1.	Data Collection - Data Pre processing
2.	Feature selection
3.	Data Splitting
4.	Model training and evaluation
5.	Model Interpretation & Model Prediction

Questions: 
•	What are the top most published books?
•	Which date was the biggest number of books written?
•	How many books received each rating and which rating?

Comparison with different models:
•	Linear regression
•	Decision tree

Results interpretation :
•	Linear regression
The predicted values are closer to the actual values compared to the previous example.    

The differences between the actual and predicted values are relatively smaller, which could indicate that your model is performing better at approximating the actual values.

•	Decision tree
Predicting values that are generally higher than the actual values. This might indicate a tendency for your model to overestimate the target variable.


