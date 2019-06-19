# Prediction-of-IMDB-Rating-using-Machine-Learning (IN PROGRESS)

## Research question and problem framing
Every year, thousands of movies are produced in the film industry. It is a multi-billion dollar industry where a tremendous amount of investment and funding is involved with each project yet so few of them achieve the commercial success. There are many factors that influence the success of a film, ranging from the cast to the popularity of the director. Considering this, it is a bit of gamble for the movie to be produced in the first place. With so much at stake, we would benefit a great deal from studying and analyzing the datasets that are available to us today. These datasets are accessible through major platforms such as Internet Movie Database (IMDB), Rotten Tomatoes, and Metacritic and contain details about the movie, ranging from the budget of a movie to the number of likes of the director. The analysis of such datasets would prove which factors are more important than others and how these factors influence the ratings of the movies. The findings of this study may be useful to the stakeholders whose decisions can greatly influence how their movie will turn out.

## Dataset
The dataset used in this study was obtained from Kaggle (https://www.kaggle.com/carolzhangdc/imdb-5000-movie-dataset) and contains information about 5,043 movies. The below are the features about the movies in the dataset. The following columns were left out of the analysis: Plot Keywords, the link to the movie page on IMDB, the aspect ratio. These features were left out because they were either irrelevant or would not be very helpful in our analysis.

## Research Methodology
The analysis of the dataset will be performed using Python. The first steps before the analysis will involve cleaning the raw dataset. The dataset will be checked for 0 and NaN values. Once this is done, all the columns that will be used as features in the models will be converted to numerical values such as integers or floats. The algorithms that will be used on the dataset are linear regression, and classification models including Random Forest and Decision Tree. Linear regression will be applied to the dataset to see how well it predicts the ratings. The classification algorithms will also be used to see how well the models classify the ratings with the selected features from the dataset. The confusion matrix will be used as the evaluator of the results. The accuracy rates or the error rate of each algorithm will be compared to determine the best performing one.
