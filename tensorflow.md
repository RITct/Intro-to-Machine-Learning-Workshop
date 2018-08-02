# Welcome to Tensorflow Study Jam !
<p align="center">
  <img src="https://scontent.fcok1-1.fna.fbcdn.net/v/t1.0-9/37838208_1074737562684398_3500528767216910336_n.png?_nc_cat=0&oh=9069a483cf036ee6b508d92e5edc12b8&oe=5C0325F3" alt="Keralaai tf study jam"/>
</p>

# Day 1
1. Intro to machine learning
2. Reducing Loss
3. Training and Testing sets
4. Logistic Regression
5. First Steps with Tensorflow

## Intro to machine learning

Machine learning is the art of making sense of data !

1. It do things normal code can't do and it helps to reduce the time you spend for coding.   

2. In machine learning we don't need to tell the algorithm what to do, we only need to show them some examples.

### Types of machine learning algorithms:
- Supervised Learning

<p>
  <img src="https://github.com/GopikrishnanSasikumar/Intro-to-Machine-Learning-Workshop/blob/master/images-2.png"alt="supervised learning"/>
</p>

- Unsupervised Learning

<p>
  <img src="https://github.com/GopikrishnanSasikumar/Intro-to-Machine-Learning-Workshop/blob/master/unsupervised_learning.png" height="200" width="400" alt="Un-Supervised Learning"/>
</p>

- Reinforcement Learning

<p>
  <img src="https://github.com/GopikrishnanSasikumar/Intro-to-Machine-Learning-Workshop/blob/master/1*HvoLc50Dpq1ESKuejhICHg.png" alt="Reinforcement Learning"/>
</p>

## Reducing Loss
content goes here
## Training and Testing Sets
<br>

<p align="center">
  <img src="http://blogs-images.forbes.com/janakirammsv/files/2017/04/ML-FaaS-1.png" height="360" width="740" alt="train-test divison"/>
</p>

1. Our goal is to create a machine learning model that generalizes well to new data. 

2. We train the model using a Training set and the test set act as a proxy for new data!


<p align="center">
  <img src="https://am207.github.io/2017/wiki/images/train-test.png" height="360" width="740" alt="train-test divison"/>
</p>

- **training set** — a subset to train a model.
- **test set** — a subset to test the trained model.

## Logistic Regression

1. Many problems require a probability estimate as output.
2. Logistic regression is an extremely efficient mechanism for calculating probabilities.
3. a sigmoid function, defined as follows, produces output that always falls between 0 and 1.

<p align="center">
  <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSw89aMI5qlmImjji48z1agmJOhIJDSJvZgrHD9WPR4q783tMEMkw" height="100" width="150" alt="sigmoid function"/>
</p>

Where,

```
y = w1x1 + w2x2 + ... wNxN
```
and p is the predicted output.



<p align="center">
  <img src="https://developers.google.com/machine-learning/crash-course/images/SigmoidFunction.png" height="400" width="500" alt="sigmoid graph"/>
</p>



**Loss function for Logistic regression is Log Loss**

<p align="center">
  <img src="https://github.com/GopikrishnanSasikumar/Intro-to-Machine-Learning-Workshop/blob/master/logloss.png" alt="sigmoid graph"/>
</p>
