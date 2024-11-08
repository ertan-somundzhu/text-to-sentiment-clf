# text-to-sentiment-clf
This is one of my NLP pet projects. It classifies texts written in English based on their sentiment (positive, negative, and neutral).

This project uses 2 ML models for this:
  1) Logit Regression (multinominal regression)

     Accuracy on training data = 0.88139750462054

     Accuracy on testing data = 0.8443275641689986
  2) Stochastic Gradient Descent Classifier (with solver set to "hinge" which gives a linear SVM)

     Accuracy on training data = 0.9250522509658512

     Accuracy on testing data = 0.8555377068435417

Libraries used: Pandas, NLTK, Re, Joblib, and Scikit-learn.

Datasets on which the models were trained: 
  1) Social Media Sentiments Analysis Dataset (sentimentdataset.csv) (https://www.kaggle.com/datasets/kashishparmar02/social-media-sentiments-analysis-dataset)
  2) Twitter Emotion (twitter emotions.csv) (https://www.kaggle.com/datasets/phantomrider/twitter-emotion)
  3) Emotion Detection from Text (tweet_emotions.csv) (https://www.kaggle.com/datasets/pashupatigupta/emotion-detection-from-text)
  4) emotion analysis based on text (emotion_sentimen_dataset.csv) (https://www.kaggle.com/datasets/simaanjali/emotion-analysis-based-on-text)
  5) Emotion Classification NLP (emotion-labels-test.csv, emotion-labels-train.csv, emotion-labels-val.csv) (https://www.kaggle.com/datasets/anjaneyatripathi/emotion-classification-nlp)
  6) Sentiment & Emotions Labelled Tweets (sentiment-emotion-labelled_Dell_tweets.csv) (https://www.kaggle.com/datasets/ankitkumar2635/sentiment-and-emotions-of-tweets)
  7) Emotion Dataset Raw (emotion_dataset_raw.csv) (https://www.kaggle.com/datasets/rikinzala/emotion-dataset-raw)



P.S. You could use the code, but the training data isn't mine, so you'll have to look up the datasets' licences.
