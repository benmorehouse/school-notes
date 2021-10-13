# chapter 5
Probability

5.1, 5.2, 5.3
----------------

Likelihood of something happen. 
random event—any event in which the outcomes observed can vary.
A fixed event is any event in which the outcome observed is always the same.

Probability is the frequency of times an outcome occurs divided by the 
total possible number of outcomes.
To calculate, need total number of possible outcomes. This is called the sample space.
WE also need the amount of times a given output can occur.

p(x) = f(x) / sample space

Probability is binary: either yes you were right or no you werent. It can never
be something that's negative.

To find the relative frequency and therefore the probability of an outcome:
- For a given event, the relative frequency of an outcome is the probability of its occurrence.


5.4, 5.5, 5.6
--------------

Multiple outcomes
The probabilities for two outcomes are mutually exclusive when two outcomes cannot occur 
together. For example, in one flip of a fair coin (the event), it is not possible to flip 
heads (Outcome 1) and tails (Outcome 2). The two outcomes for this event are mutually exclusive. 
The probability that they occur together is 0. We can represent the probabilities of two mutually 
exclusive outcomes (A and B) symbolically as follows:

p(A⋂B) means that they are mutually exclusive.

p(A u B) means that one or the other could occur, but not both. 

p(A u B) = p(A) + p(B)

The additive rule, also called the additive law, states that when two outcomes for a given event are mutually exclusive, the probability that any one of these outcomes occurs is equal to the sum of their individual probabilities.

The probabilities for two outcomes are independent when the probability of one outcome does not affect the probability of the second outcome. For example, if we flip a fair coin two times (the event), it is possible to flip heads 
(Outcome 1) on the first flip and heads (Outcome 2) on the second flip. The probability of the first outcome has no effect on the probability of the second outcome. The two outcomes are independent.

When they are independent, the probability of them happening is equal to the product of their individual probabilities.
p(A⋂B) = p(A) × p(B).

Complimentary outcomes means that their probabilities equal 1.
In a study where it's heads or tails, the probability of it being heads
or tails is complimentary.

Conditional outcomes means that the probabilty of one outcome is conditional upon the 
outcome of another thing happening.
For example, suppose you want to determine the probability of drawing two heart cards from a fair deck of cards.
The probability of drawing the second one is based on drawing the first one.

The virgule (/) symbol in the parentheses is read as “given that.”

p(U/P) = p(P⋂U) / p(P)


5.7, 5.8, 5.9
--------------
the probability distribution of a random variable. That is, the probability of obtaining each possible outcome of a random variable.
The sum of probabilty distribution of all possible outcomes will equal 1 in a set of things.
A random variable is a variable obtained or measured in a random experiment.

The mean of a propability distribution just means the mean of the expected outcome of a given random variable.
To illustrate, suppose we flip two fair coins three times and observe two heads face up on each flip. The random variable is the number of heads per coin flip. The possible outcomes of the random variable are 0, 1, and 2 flips of heads.
µ = (0 × .25) + (1 × .50) + (2 × .25) = 1.00.

Suppose you are offered the choice between having a 100% chance of receiving $3,000 and having an 80% chance of receiving $4,000 with a 20% chance of receiving nothing. Which do you choose?


5.10, 5.11, 5.12
-----

To determine the distribution of all other outcomes for a given random variable, we compute the variance and standard deviation of all other outcomes in a probability distribution.
Take the square root of the variance.
The variance of a probability distribution is a measure of variability for the average squared distance that outcomes for 
a given random variable deviate from the expected value or mean of a probability distribution. The standard deviation of a probability distribution is a measure of variability 
for the average distance that outcomes for a given random variable deviate from the expected value or mean of a probability distribution. It is calculated by taking the square root of the variance of a probability distribution.

binomial probability distribution:
The distribution of probabilities for each outcome of a random variable with two possible outcomes is called a binomial probability distribution.

when there are only two possible outcomes, the mean is the number of times the variable is observed and the probability of its outcome.

For the variance of binomial distribution is np(1-p).



