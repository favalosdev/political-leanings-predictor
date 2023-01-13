# political-leanings-predictor

A simple classification model for predicting the political leanings of an user given its tweets.

## Core assumptions

So, the task of extracting which tweets are known to be as pertaining to certain political ideology kind of defeats the purpose of this model. However, some assumptions can be made despite of not being entirely accurate. That said, this model relies on the assumption that if a candidate or spokeperson's of a political party likes or endorses some tweet, then that tweet can be considered as an ideologically representative corpus of text.

## General workflow

If you are lazy or you just don't want to spend hours trying to wrap your head around the code, don't worry, the general workflow of the project is rather easy to understand.

The project is divided in three big stages: data collecting, pre-processing and model fitting. The first one is achieved by using Web Scraping techniques in order to retrieve a representative amount of tweets for each main ideology of the Colombian political spectrum (left, center or right). The second is done by employing standard methods for text cleaning. In this stages important decisions should be made - for example, as to if it is necessary to remove stop words or choose between stemming and lemmatization. The third and final stage is straightforward. In it is where a neural network (concretely, a MLP) is created and later on, fitted. Useful metrics for assessing the model's performance are included.
