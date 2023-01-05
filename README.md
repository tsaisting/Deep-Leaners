# Deep-Leaners

## Introduction
The number of movies released each year has steadily increased from 2000 onward in North America. Being faced with an ever-increasing selection, viewers and critics have developed a range of criteria to review the quality of movies. Social media platforms are rife with fan followings and hate clubs for different movies. We see the effect of these opinions in the movie ratings the film receives. A high movie rating shows how successful and popular the movie is. Movie success is crucial since billions of dollars are invested in making them (Rijul, 2018).

What makes a movie lucrative triggers the interests of researchers worldwide, and there is a lot of research in this regard. Ensemble learning algorithms, like random forest and XGBoost, were used to predict movie rating with social media data and showed the popularity of directors, actors, and writers affected movie rating most (Zahabiya & A.Razia, 2020). Other research indicated duration and budget were deemed more important than the facebook popularity of directors and actors (Sun, 2016). The number of audiences played a vital role in movie rating (Rijul, 2018).

However, previous research has generated inconsistent results on the features that determine a successful movie. Some use data from social media platforms (Facebook, YouTube) that are not reliable for movie reviews. Some of them use small-scaled data covered in recent years.
We aim to predict movie ratings based on movie features using a reliable data set in this project. We are interested in digging deeper into the data to explore which attributes are the most important for a successful movie. This project uses machine learning algorithms to predict movie ratings and provides an investment guide for movie productions and a recommendation platform for audiences to choose high-quality films.

## Data description
This data set is an IMDb movie extensive data set from Kaggle.
(https://www.kaggle.com/stefanoleone992/imdb-extensive-dataset). IMDb (Internet Movie Databases) is an online database of information related to movies and TV series that include plot summaries, ratings, and reviews. 

There are almost 600,00 movies recorded on IMDb in September 2021. This data set contains four files, movies, names, ratings, and title principles. The movies file comprises 85,855 movie description instances from 1910 to 2020 and 22 attributes, like title name, released year, movie genre, duration, movie language, directors, etc. The rating file contains the weighted average rating, total votes, mean vote, median vote, age group, and gender voting patterns. The names file contains the information of actors, and the title principals file has information about the actor’s role in each movie. The four files have a unique movie title ID and a unique name Id for each person. 

The target variable we are concerned with for this project is the average movie rating. We make use of seven features in our model. Six out of the seven are numeric features: duration, budget, year released, total votes, the average rating of director,  and the weighted average rating of the cast. The movie genre is the only discrete categorical feature. 

## Models
For this project, our SMART questions were to predict movie ratings with a regression model and recommend good movies with a classification model. Therefore, we chose the linear regression model for the first question and the logistic regression model for the second question. After finishing the linear regression model, we gained feature importance by building a decision tree model.
