# toxic-comment-classification
Detecting different types of toxicity using NLP
Dataset from [Kaggle Toxic Comment Classification Challenge](https://www.kaggle.com/c/jigsaw-toxic-comment-classification-challenge/)

## Objective
The goal of this project is to use common NLP tools and concepts to classify raw text comments. This includes text cleaning, tokenization, one-hot encoding of tokens, learning word embeddings, evaluation metrics for classification.

Once we have analyzed the data set, cleaned the data, and extracted features; we will do modeling starting with a simple log reg baseline. Then we will improve on this using deep neural networks
and recurrent neural networks. We will also use pretrained word embeddings to improve our metrics.

## How to replicate
Download the data from [here](https://www.kaggle.com/c/jigsaw-toxic-comment-classification-challenge/data).

Open the notebook file using Jupyter Notebook, or with Google Colab.

## Deployment Ideas
Build a simple front-end with a text box which takes in raw text as input, and classifies the text. Use Flask server running on a Docker container to host the app. Consider ECS Fargate containers for deployment.

## Resources
https://machinelearningmastery.com/how-to-reduce-overfitting-in-deep-learning-with-weight-regularization/
https://machinelearningmastery.com/how-to-reduce-overfitting-with-dropout-regularization-in-keras/
https://danijar.com/tips-for-training-recurrent-neural-networks/
https://towardsdatascience.com/multi-class-text-classification-with-lstm-1590bee1bd17
https://towardsdatascience.com/multi-label-text-classification-with-scikit-learn-30714b7819c5
https://towardsdatascience.com/journey-to-the-center-of-multi-label-classification-384c40229bff
