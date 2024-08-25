This project delves into the dynamics of music popularity, aiming to uncover the underlying
determinants of song success through regression modelling. Understanding the factors that
contribute to the popularity of songs within the context of a digital music platform like
Spotify presents an intriguing avenue for exploration.
Exploratory data analysis techniques are employed to gain a deeper insight into the underlying patterns of the dataset, and to observe any variability of statistical properties of
variables based on whether the songs are popular or not.
Using a Kaggle dataset comprising over 100,000 songs, a methodical approach integrating regression modelling techniques is employed to find out the multifaceted relationship
between song attributes and popularity scores.
We apply multiple linear regression (MLR) using all the song features with the popularity
score as the dependent variable. Subsequent methodological refinements, including Principal Component Regression (PCR) and MLR on reduced features, are applied to handle
multicollinearity issues.
Due to the failing nature of the linear regression models on the full dataset, an undersampling procedure is performed to balance the dataset, emphasising more on the relevant
popularity scores. MLR is then, finally, trained on data which was extracted based on
different popularity cutoffs, which gives us comparable results.
To estimate the error analysis of the final model, the Jackknife method is used to extract
the properties of the outliers that the data can potentially possess.
Finally, we also apply Logistic Regression (Logit Model) to predict whether a song is
‘Popular’ or ‘Non Popular’.
The process of setting the cutoff, sampling, running the logistic regression, and then
evaluating the outputs of the model is repeated for several different cutoff points, and we
ended up with some promising results.
