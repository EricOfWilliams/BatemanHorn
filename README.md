# BatemanHorn
The Bateman-Horn Conjecture gives an asymptotic estiamte to the density of primes in the output of a polynomial.
If *Q(f; x)* is the number of *n ≤ x* such that *f(n)* is prime, the Bateman-Horn Conjecture predicts that *Q(f; x)* is asymptotically equivalent to a certain constant times the offset logarithmic integral *Li(x)*.
My honors project involved exploring what the Bateman-Horn Conjecture predicts for the polynomial *x<sup>2</sup> + x + k*.
This repository contains a pair of Sage notebooks that allow the user to:
1. Compute the constant *C(f)* for *f(x) = x<sup>2</sup> + x + k*
2. Plot the prediction made by the Bateman-Horn Conjecture vs. the actual count of the primes.
