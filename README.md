# TMBD-Box-Office-Prediction

Here, I have only made use of the provided data.  Many other users have imported external data to improve model accuracy, but for the 
purposes of this kernel I've only used the competition's original data to do EDA, FE, and model building using LGBM.  The final RMSLE for this kernel is 2.70603.  This could be improved considerably using the functions written here and then applied to external data.


Link to Kaggle competition: https://www.kaggle.com/c/tmdb-box-office-prediction
Per the competition description:

We're going to make you an offer you can't refuse: a Kaggle competition!

In a world... where movies made an estimated $41.7 billion in 2018, the film industry is more popular than ever. But what movies make the most money at the box office? How much does a director matter? Or the budget? For some movies, it's "You had me at 'Hello.'" For others, the trailer falls short of expectations and you think "What we have here is a failure to communicate."

In this competition, you're presented with metadata on over 7,000 past films from The Movie Database to try and predict their overall worldwide box office revenue. Data points provided include cast, crew, plot keywords, budget, posters, release dates, languages, production companies, and countries. You can collect other publicly available data to use in your model predictions, but in the spirit of this competition, use only data that would have been available before a movie's release.

Join in, "make our day", and then "you've got to ask yourself one question: 'Do I feel lucky?'"

