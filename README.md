# Machine Learning Engineer Nanodegree

# Deep Learning

## Project 1: Deploy a Sentiment Analysis Model using AWS SageMaker

### By Vedavyas Kamath


### Overview
This project is to build and train a recurrent neural network for the purpose of determining the sentiment of a movie review using the IMDB data set. I have created a model using Amazon's SageMaker service. In addition, I have deployed my model and also constructed a simple web app which will interact with the deployed model, to accept an input review first and then display the prediction of whether the review is positive or negative based on the words entered in the review.

### Dataset:
For this project we used the Large Movie Review Dataset v1.0 - which contains movie reviews along with their associated binary sentiment polarity labels for approx 50,000 reviews and is intended to serve as a benchmark for sentiment classification. [See here](http://ai.stanford.edu/~amaas/data/sentiment/)

### Goal/Aim
To build a setiment classifier using RNNs and train it with data for different reviews included in the IMDB dataset of reviews so that the model is able to predict if a new review given as input is positive or negative.

### Software Requirements
This project requires **Python 3.x** and the following Python libraries installed:

- [SageMaker](https://sagemaker.readthedocs.io/en/stable/)
- [PyTorch](https://pytorch.org/docs/stable/index.html)
- [NLTK](https://www.nltk.org/)
- [NumPy](http://www.numpy.org/)


### Instructions
Please see the [README](https://github.com/udacity/sagemaker-deployment/blob/master/README.md) in the root directory for instructions on setting up a SageMaker notebook and downloading the project files (as well as the other notebooks).

### Citations
[ACL 2011 paper](http://ai.stanford.edu/~amaas/papers/wvSent_acl2011.bib)

