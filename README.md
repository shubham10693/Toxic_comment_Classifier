# Toxic Comment Classifier

This project is related to Jigsaw Toxic comment competition fron kaggle. The goal of this project is to create a Toxic comment classifier using ML techniques to filter out the toxicity present in a sentence.

I have initially created a Toxic comment classifier using Logistic regressions, Multinomial Naive Bayes and Random Forest algorithms. For my Data mining final project I have used LSTM technique to increase the accuracy of the model.

I have also deployed the model on Heroku platform, using Flask which is a normal UI where one can type in a toxic comment and the result will show the toxicity which is present in the comment. 

Pickle files for each feature of the dataset are present in the files, which can be used in the flask to deploy the features in the Heroku.

**Instructions to run this code :**

1. Download python and jupyter notebook. If required you can use google colab as it provides GPUs and TPUs of their own so that the project can run faster as the dataset is huge.
2. You can download the data from kaggle website https://www.kaggle.com/c/jigsaw-toxic-comment-classification-challenge/data
3. Once you have downloaded the dataset you can use the Toxic_comment.ipynb to run the program. (Note: This does not uses the LSTM, and gives accuracy around 70-75%)
4. You can use 
5. For deployment purpose, you can deploy it using Heroku, by using Flask. Only the Toxic_comment.ipynb can be deployed. All the backend and front files are provided in the repository along with pickle files that can be used in the Flask.

Image Preview of my deployed Model : 

![image](https://user-images.githubusercontent.com/19195445/145139458-c85b1f57-9617-4afc-9b00-ffa45d8ffdb9.png)
![image](https://user-images.githubusercontent.com/19195445/145139511-9da87c6d-7efb-4c37-a24e-c8109c1e3e60.png)
