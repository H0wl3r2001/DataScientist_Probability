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

## Probability Frequency Distribution

The Probability Frequency Distribution(PFD) is a collection of the probabilities for each possible outcome of an event. We need this in order to try and predict future events when the expected value is unattainable.

In other words, it can be presented as a table matching each distinct outcome in the sample space to its frequency (number of times a given outcome appears in the sample space). We obtain the PFD by dividing each frequency by the size of the sample space. An example table is presented below:

$$
\begin{array}{|c|c|c|}
\hline
\textbf{Class Interval (Score Range)} & \textbf{Frequency (f)} & \textbf{Relative Frequency} \\
\hline
40 - 49 & 3  & 1/10 \\
50 - 59 & 5  & 1/6 \\
60 - 69 & 7  & 7/30 \\
70 - 79 & 8  & 4/15 \\
80 - 89 & 4  & 2/15 \\
90 - 99 & 3  & 1/10 \\
\hline
\end{array}
$$

This is an example table representing the score distribution, in intervals, of an hypothetical exam.

## Complements

A complement of an event is everything not in its scope. The denotation is the following:

$$
A' = \neg  A
$$

Furthermore, the complement follows the ensuing properties:

- Can never occur simultaneously to the event;
- Its sum with the event is the sample space and their respective probabilities add upto 1 ($A + A' = Sample Space \Rightarrow P(A) + P(A') = 1$);
- The complement of a complement is the original event ($(A')' = A$);

## Contents

Following this brief introduction, this step on the roadmap contains the following subjects, each within a Jupyter notebook:

- Combinatorics;
- Bayesian Inference;
- Distributions.

Furthermore, the project provides a **yml** extension file with the virtual environment's specifications.
