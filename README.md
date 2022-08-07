# Spotify competition: Predicting sequential track-skipping
## Built XGBoost with 76.8% accuracy

I competed in the Spotify Sequential Skip Prediction Challenge, and emerged top 7% out of 1350 participants.
<br>
<li> Windowed feature engineering for sequential information.
<li> Regularized k-fold target encoding of categorical features.
<li> Hyperparameter tuning using Bayesian Optimization.
<li> Threshold-moving to minimize expected costs in real-world model deployment.
 
# About
A central challenge for Spotify is to recommend the right music to each user. While there exists a large body of work on recommender systems, there is at present little work describing how users sequentially interact with the streamed content they are presented with. Music content is unique in that the question of if, and when, a user skips a track is an important implicit feedback signal on the quality of the system's recommendation.

I explore this important and understudied problem in music streaming by building a machine learning model that predicts whether a user will skip or listen to tracks that they are streamed, given their immediately preceding interactions in a listening session.

# Project Methodology
1. Feature engineering to capture sequential information
2. Encode categorical features using regularized k-fold target encoding
3. Select metric of focus: F2-Score
4. Train and tune XGBoost using Bayesian Optimization

# Still curious?
Check out this project on my website <a href="https://sheilateozy.github.io/#portfolio">here</a> :)


