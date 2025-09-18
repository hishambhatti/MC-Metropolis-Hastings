# Monte Carlo Metropolis-Hastings

A formal proof that the average error of Monte Carlo Integration converges to 0, and an example using the Metropolis-Hastings algorithm to compute the expectation of an unknown distribution.  

This paper was submitted for Math 336: Honors Advanced Calculus in Spring 2023. Thank you Prof. Steinerberger for being an inspiring lecturer and always breaking the mold!

[Pic of the thing]

## Summary

Scientists are often presented with a complicated domain and function where standard closed-form integration techniques fail. Monte Carlo Integration aims to overcome this challenge by using random sampling to provide a probabilistic approximation to a deterministic problem. With this method, we formally prove that the average
error is 0, with the average magnitude decreases as a function of 1/√N of sample size N. Applying this algorithm allows us to compute the volume of the 10-dimensional unit sphere to within 0.2% of the actual value. 

We then re-frame this problem in the context of generating random, representative samples from an unknown distribution. The Metropolis-Hastings algorithm provides one such approach, constructing a Markov Chain with each sample conditioned on its prior. Its usage of correlated samples creates a distribution that converges much quicker to the unknown distribution than standard rejection-sampling.

[Comparison of Rejection sampling and Monte-Carlo sampling]

We conclude with a comparison between rejection sampling and the Metropolis-Hastings Algorithm in the context of computing an expected value of an unknown distribution, highlighting the increased accuracy and stronger rate of convergence of this method.

Please feel free to read the paper and explore the notebooks!

## Tools
Python, Jupyter Notebook, Google Colab, LaTeX

## Credit
* Dr. Stefan Steinerberger -- thanks for always challenging us!
* My MATH 336 Classmates: it really is always Monte Carlo and Cauchy-Schwartz

We then re-frame this problem in the
context of generating random, representative samples from an unknown distribution.
The Metropolis-Hastings algorithm provides one such approach, constructing a Markov
Chain with each sample conditioned on its prior. Its usage of correlated samples creates
a distribution that converges much quicker to the unknown distribution than standard
rejection-sampling. We conclude with a comparison between rejection sampling and
the Metropolis-Hastings Algorithm in the context of computing an expected value of
an unknown distribution, highlighting the increased accuracy and stronger rate of con-
vergence of this method.
