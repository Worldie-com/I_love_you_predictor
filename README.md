I_love_you_predictor
==============

I Love You Predictor
Started like a funny discussion during an hackatown, this experiment was about building a predictor able to predict if in the next conversation between a male and female one of them would declare his love to his patner, telling him/her: "I love you" 
Using a movie-conversation dataset composed of 220,000 conversations from movies, we have used selected all the couple that has had a conversation.
Then, for each couple we have listed all the conversation and, in case one contains "I love you", selected the previous 5 conversations.
In case a couple's conversations doesn't contains any "I love you", we have selected randomly a group of of 5 following conversation.
Then, build a predictor on Azure that looks to work really well:
![Model Performance](https://dl.dropboxusercontent.com/u/7335663/machine_learning_experiment/IsFallingInLove.png "Performance Predictor of IS FALLING IN LOVE")

To train and validate the model we have used the followig dataset
https://dl.dropboxusercontent.com/u/7335663/machine_learning_experiment/I_love_you_predictor.csv

This project contains some Apache Spark code used to build the data-set, starting from the original csv files of the full movie-datasets



