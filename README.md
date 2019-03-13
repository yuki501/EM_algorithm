# EM_algorithm
(a) The parameters of Gaussian Mixture Model (GMM) can be estimated via the EM algorithm. Show that the alternating algorithmfor k-means (in Lec. 11) is a special case of the EMalgorithmand show the corresponding objective functions for E-step and M-step.

(b) Download the Old Faithful Geyser Dataset. The data file contains 272 observations of (eruption time, waiting time). Treat each entry as a 2 dimensional feature vector. Parse and plot all data points on 2-D plane.

(c) Implement a bimodal GMMmodel to fit all data points using EMalgorithm. Explain the reasoning behind your termination criteria. For this problem, we assume the covariance matrix is spherical (i.e., it has the form of \sigma^2 for scalar \sigma) and you can randomly initialize Gaussian parameters. For evaluation purposes, please submit the following figures:
  • Plot the trajectories of two mean vectors in 2 dimensions (i.e., coordinates vs. iteration).
  • Run your program for 50 times with different initial parameter guesses. Show the distribution of the total number of iterations needed for algorithmto converge.
  
(d) Repeat the task in (c) but with the initial guesses of the parameters generated from the following process:
  • Run a k-means algorithm over all the data points with K = 2 and label each point with one of the two clusters.
  • Estimate the first guess of the mean and covariance matrices using maximumlikelihood over the labeled data points.
  Compare the algorithm performances of (c) and (d).
