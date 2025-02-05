# Data Scientist Probability

## Introduction to Probability

Understanding the fundamentals behind key concepts about probability and further ahead statistics is crucial when studying Data Science. It will allow us to gain insight when analysing data when using supervised machine learning models (for example, regressions), but also start to understand the logic behind unsupervised models.

By definition, probability is the likelyhood of an event happening. Event can be a specific outcome or the combination of several outcomes. It is measured with numbers between 0 and 1, and the general formula is the following:

$$
P(X) = \frac{X}{N}
$$

where X is the outcome we are trying to measure and N is the total number of possible outcomes in the scenario.

## Expected Values

This are the specific outcomes we expect to occur while running an experiment. An experiment is a collection of trials, and a trial is essentially observing an event and recording its outcome. Furthermore, an experimental probability is the probability we assing to an event, based on an experiment.

A good example is the experiment of flipping a coin N amount of times. Each coin flip is a trial, the experimental probability would be the number of heads we record over the N amount of flips. 

The expected value depends on the can be numerical, Boolean, categorical or other, depending on the type of the event we are interested in. For instance, the expected value of the trial would be the more likely of the two outcomes, whereas the expected value of the experiment will be the number of time we expect to get either heads or tails after the N amount of trials.

The formula of expected value for categorical variables is:

$$
E(X) = n*p
$$

whilst the formula for numeric values is:

$$
E(X) = \sum_{i=1}^{n} x_i * p_i
$$