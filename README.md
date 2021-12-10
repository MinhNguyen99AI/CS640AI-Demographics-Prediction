# CS640

Final Project CS640 Boston University

Group Members:

  Finn Jensen
  
  Nick Zotalis
  
  Keith Tyser
  
  Aditya Agrawal
  
  Minh Le Nguyen

Project Write Up: https://docs.google.com/document/d/1hGIXt37YPBSDi7Lcl1acnfngKjwQA4o16ffWl9D9DpQ/edit?usp=sharing

Project Pptx presentation: https://docs.google.com/presentation/d/15-OCQ7yshScdmePRDjTCr6ZV4McLflT1vGuGkbD3Dgw/edit?usp=sharing

Project Google Drive file: https://drive.google.com/drive/folders/1c1zewNOxhhgYFve1eFI4y3HFJ_fKWm-C?usp=sharing

 
PROJECT PROBLEM DESCRIPTION: 

Topic:
(3)	Demographic (Age (<21 and >=21) and Race (black, white, Hispanic/Latino, Asian) prediction of Twitter users. You are allowed to but are not required to predict the multiracial class. The data for this project is available in this directory. The training data is in the file labeled_users.csv in the directory. Description about this data can be found in the file README in the directory. 

Your task is to use tweets of these Twitter users (available in the Twitter_User_Handles_labeled_tweets.json file) to predict their age (<21 and >=21) and race (black, white, Hispanic/Latino, Asian) based on the training data available in the labeled_users.csv file. You can also use the profiles of these Twitter users (available in the User demo profiles.json file) to augment your training. 

You can use the user’s Twitter user_id in labeled_users.csv to obtain the user’s last 100 tweets in the file Twitter_User_Handles_labeled_tweets.json 

Similarly, you can use the user’s Twitter user_id in labeled_users.csv to obtain their profiles (name, screen name, description, link to profile picture in the profile pics.zip file) in the file User demo profiles.json. You can use library such as ethnicolr to predict the race of the users from their names, and use these predictions to augment your training data for predicting race from tweets. You can also train a model for predicting race from the profile picture of the user or use dataset (and code) from VMER or UTKFace or others to train the model for predicting race from the profile picture. You can also use method described in this tutorial code to extract faces from the image and turn them into embeddings which you can use as features for your race prediction model. 

You will build 2 models, one for predicting age and another for predicting race (you can use the same model for both tasks). 

Report the approach(es) you take for each of this task and their 5-fold cross-validation accuracies for age classification and for race classification (on the labeled data where age is not null and race is not null, respectively), and the per-class precision and recall (<21 or >=21 for age, and black/white/Hispanic-Latino/Asian for race). 

You will be graded based on your (a) presentation and (b) write up including the link to your code (shared through GitHub/Google Colab) – particularly, how do you think through the problem and whether the approach you do make sense for the problem and the data, and the insights you obtain. 

The current performances and approaches that have been tried can be found the file stats_race_&_age.pdf. The 5-fold cross validation accuracy for the 4 classes of race is 0.67. You don’t have to match the performance, but if you outperform the current multi-class performance for either age or race, we will award +15 bonus points each (so +30 bonus points if you improve both) for your project. 
