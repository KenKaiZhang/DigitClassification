# Digit Classification

_This code is based on [Building a Neural Network from Scratch](https://www.youtube.com/watch?v=w8yWXqWQYmU&t=1697s)_ by Samson Zhang.

## Overview

The goal of this project is to create an neural network that can take a image of a handwritten digit and predict it. The digit will range from `0` to `9`.

To train this neural network, we will be using the **[MNIST Dataset](https://www.kaggle.com/competitions/digit-recognizer/data)** available on the Kaggle. This dataset will include 42000 example of low resolution, handwritten digits where each image is the size of 28x28 pixels.

The neural network will consist of 3 layers:

1. input
2. hidden
3. output

Each layer will perform the same linear operation along with their own activation functions.

## Prerequisite

You will need a Kaggle account and retrieve a free API key that will be saved in `kaggle.json`

## Content

There is only one file for this project.

`digit_classification.ipynb` contains the code and explainations.

## Results

Here is an example of the accuracy of the model after 1000 iterations where.

```
Iteraation: 0	Accuracy: 0.04830952380952381
Iteraation: 50	Accuracy: 0.7195238095238096
Iteraation: 100	Accuracy: 0.8093095238095238
Iteraation: 150	Accuracy: 0.8468095238095238
Iteraation: 200	Accuracy: 0.8672619047619048
Iteraation: 250	Accuracy: 0.8844761904761905
Iteraation: 300	Accuracy: 0.8921666666666667
Iteraation: 350	Accuracy: 0.8977857142857143
Iteraation: 400	Accuracy: 0.9027380952380952
Iteraation: 450	Accuracy: 0.9057857142857143
Iteraation: 500	Accuracy: 0.9078571428571428
Iteraation: 550	Accuracy: 0.9115714285714286
Iteraation: 600	Accuracy: 0.9136428571428571
Iteraation: 650	Accuracy: 0.9154761904761904
Iteraation: 700	Accuracy: 0.917404761904762
Iteraation: 750	Accuracy: 0.9188571428571428
Iteraation: 800	Accuracy: 0.9200238095238096
Iteraation: 850	Accuracy: 0.9210714285714285
Iteraation: 900	Accuracy: 0.9229285714285714
Iteraation: 950	Accuracy: 0.9237142857142857
Iteraation: 999	Accuracy: 0.9245714285714286
```

By running the `make_prediction()` function, given a number between `0` to `41999`, we should be able to predict the digit represented in that example.