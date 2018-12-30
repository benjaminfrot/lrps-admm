# lrps-admm
An (accelerated) Alternative Direction Method of Multipliers implementation of the low-rank plus sparse estimator.

See here for a tutorial: https://nbviewer.jupyter.org/github/benjaminfrot/lrps-admm/blob/master/LRpSADMMExample.ipynb

This code will soon be made into an R package. 

In addition, we show how to combine this estimator with the GES algorithm and IDA in order to estimate causal effects. An implementation of the Kendall based correlation matrix estimator is also provided.

We implement the estimator described in: https://projecteuclid.org/euclid.aos/1351602527 .

This R implementation uses an accelerated version with restarts of the ADMM algortihm, as described in: ftp://ftp.math.ucla.edu/pub/camreport/cam12-35.pdf .

