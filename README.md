# -Kaggle-s-Machine-Learning
https://www.kaggle.com/kiranmaharjan/my-model-bfa404/notebook
Underfitting, Overfitting and Model Optimization

Building Your Model
You will use the scikit-learn library to create your models. When coding, this library is written as sklearn, as you will see in the sample code. Scikit-learn is easily the most popular library for modeling the types of data typically stored in DataFrames.

The steps to building and using a model are:

Define: What type of model will it be? A decision tree? Some other type of model? Some other parameters of the model type are specified too.
Fit: Capture patterns from provided data. This is the heart of modeling.
Predict: Just what it sounds like
Evaluate: Determine how accurate the model's predictions are.

Experimenting With Different Models
http://i.imgur.com/2q85n9s.png

Overfitting: capturing spurious patterns that won't recur in the future, leading to less accurate predictions, or
Underfitting: failing to capture relevant patterns, again leading to less accurate predictions.

Of the options listed, 50 is the optimal number of leaves. Apply the function to your Iowa data to find the best decision tree.
