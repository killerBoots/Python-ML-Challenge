# Python-ML-Challenge

FIMT-India: Python Challenge - Question 1

Challange Description:

Background:

In this first problem let us play with probability distributions. 

A random variable is a numerical description of the outcome of an experiment. For example a random variable `x` may denote
the outcome of a coin toss. If you are interested, you can read more about random variables from
https://www.mathsisfun.com/data/random-variables.html 

The probability distribution for a random variable describes how probabilities are distributed for values of the random
variable. For a discrete randome variable `x`, a probability function denoted by `f(x)`, provides the probability for each value of
the random variable. For example, `f(x)` the probability of obtaining x on a roll of dice will be a constant function with value
1/6  for `x` ranging from 1 to 6. There are various discrete probability distributions such as poisson, binomial and 
hypergeometric. Enthusiastic participants may read more about probability distribution of random variables from Chapter 3 of
this extremely lucid text book https://www.openintro.org/download.php?file=os3_tablet&referrer=/stat/textbook.php

The poisson probability distribution is often used to model random arrivals in waiting line simulations. The poisson prbability
distribution f(x) gives the probability of x occurences in an interval. For examples, `f(x)` could be the probability of `x`
customers arriving at an ATM during a one minute interval.  Let m be the mean number of occurences of an event in a time
interval. For the time interval, the formula for `f(x)` is:

`f(x) = (m ** x) * (e ** m) / x!`  where e is natural logaritm (https://en.wikipedia.org/wiki/E_(mathematical_constant))


Problem:

Phone calls arrive at the rate of 48 per hour `(m = 48)` at the reservation desk of a hotel. Write a function
getArrivalProbability that takes as its input the number `x`, and returns as its output the probability that `x` or less than `x`
number of phone calls will arrive in an hour.

Tip:

For `x = 2` you need to return the sum of `f(0)  + f(1) + f(2)` where `f(x)` is computed using the formula for poisson distribution.

For `x=n` you need to return the sum of `f(0) + f(1) + …… f(n)` where `f(x)` is computed using the formula for the poisson
distribution
                         
Evaluation: 

Solution submission guideline:

We have provided a sample ipython notebook aXXXXXX_Q1.ipynb. Download and save the file, and change the XXXXXX in the file name
to your corp id. For example if your corp id is 111111, then the name of your file should be a111111_Q1.ipynb. Please maintain
this file name while uploading your solution to upload.fmr.com

In the file we have a function with signature
`def getArrivalProbability(x):`

Please provide your solution as implementation of this function
Use the sample template available at: https://xxxxxxxx.com/docs/DOC-946624 

Please note that you will require Anaconda Python 3 distribution to open the ipython notebook. The instructions for installing
the Anaconda distribution is available at https://xxxxxxxxxx.com/docs/DOC-946623
                    
Reward:
  
Start Date:

September 27, 2017

End Date:

October 7, 2017


http://xxxxxxx.com/9swcIL
