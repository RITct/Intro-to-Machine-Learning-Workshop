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
content goes here
## Reducing Loss
content goes here
## Training and Testing Sets
<br>

1. Our goal is to create a machine learning model that generalizes well to new data.

2. We train the model using a Training set and the test set act as a proxy for new data!


<p align="center">
  <img src="https://am207.github.io/2017/wiki/images/train-test.png" height="360" width="740" alt="train-test divison"/>
</p>

- **training set** — a subset to train a model.
- **test set** — a subset to test the trained model.

### Wait, but there is a problem...

3. Dividing the data set into two sets is a good idea, but not a panacea. You can greatly reduce your chances of overfitting by partitioning the data set into the three subsets shown in the following figure:

<p align="center">
  <img src="https://am207.github.io/2017/wiki/images/train-validate-test.png" height="360" width="740" alt="train-test divison"/>
</p>

4. Use the validation set to evaluate results from the training set. Then, use the test set to double-check your evaluation after the model has "passed" the validation set.

- **Validation set** - A subset of the data set—disjunct from the training set—that you use to adjust hyperparameters.

