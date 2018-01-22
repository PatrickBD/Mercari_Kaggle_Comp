# Mercari_Kaggle_Comp
A RNN, Ridge, and RidgeCV aggregate model for the Mercari Kaggle competition (RMSLE score of 0.427) 

Here is the compo page: https://www.kaggle.com/c/mercari-price-suggestion-challenge
The original Kernal can be tried and run here: https://www.kaggle.com/valkling/mercari-rnn-2ridge-models-with-notes-0-42755

The Mercari Price Suggestion Challenge is a $100,000 machine learning competition on Kaggle. The goal being to predict the sale price of items on Mercari. Mercari wants to have this prediction so that it can suggest to it's users what price new postings are likely to sell at. 

As an added complication, the challenge only allowed submissions using Kaggle kernals. This means that everyone's code is run on a simulated computer, about as powerful as a good desktop computer,  and has a time limit of 1 hour. No additional dataframes can be saved or brought in between runs.

My model is an aggregate a RNN and 2 Ridge models. It is kept in a jypiter notebook here or in the notebook kernal on Kaggle. It is probably best to view the Kaggle kernal, as all the test and train files are there and ready to explore. If using this GitHub, the test and train files will still need to be picked up on the challenge page. I did good in the compo, I was in the top 100 for a while. I decided that I had other projects to work on so I left it at this point. I published this notebook as a tutorial for others in the compo. As such it has many notes and ideas in the markdowns and comments. It is the best scoring public kernal of the compo as of this posting.
