# avocado-o-meter-fruit-classification-notebook - v1.0.0

## Fruit classifier model

Part of the goal was to train a model capable of classifying fruits.

After several attempts using Tensorflow I was not able to train a model with the enough accuracy. That is why I decided to go with an amazing library called [fastai](https://www.fast.ai/).

I was able to build a state-of-the-art model with 0.268420 error rate. I trained the model during four epochs. 

## Dataset
The model was trained to classify between 262 types of fruits using the [Fruit-262 Dataset](https://www.kaggle.com/aelchimminut/fruits262)

## Training Tool

First try was to use Google Colab to train the model but it was not posible due the limitations. 
I discovered an great platform from AWS called [Amazon SageMaker](https://aws.amazon.com/pm/sagemaker/)

The whole process was a great opportunity to learn a lot of new things on the ML/Deep Learning field.