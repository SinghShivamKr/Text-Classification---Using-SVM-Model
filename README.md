# Text-Classification---Using-SVM-Model
Text Classification - Using SVM Model

I'm Dividing my Project into 4 Parts.

1. i was collect data via (Kaggle Dataset)
    store my data in my local pc with the name of spam.csv

2. Feature Engineering  (Data Cleaning)
    After my data storing. i was read this CSV file for classification.
    There are a lot of null values, first, I remove that kind of value.
     After removing the null value I was visualizing ham and spam value for better understanding.

3. Feature Selection
    In this part, 70% of model predictions affect future results.
    The major issue for me hue amount of data and how I convert it in vectorize form, there is a lot of option like Bag of words, TF-IDF, WordtoVec. firstly I use Bag of words and lemmatize my data and remove my stopwords and convert my data in a vector form. But after using a Bag of words model, my prediction accuracy is not good. so I decide to go with TF-IDF Vectorizer. By using this my model work pretty much better.

4. Model Deployment  
    Well, there is no documented idea which model is good for classification. so I was the start with the Logistic classification model. It gives me a good result, with 97% accuracy but I'm not satisfied with this result. so I tried another model is SVM and after that, it's given me 99% Acuracy
