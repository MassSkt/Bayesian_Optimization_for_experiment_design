This notebook works on google colaboratory.
(Especially the optimizing process animation code is written for google colab)

# Method 
Gaussian process (GP) is used for optimization.
GP model fits to the data (X input and y output) which is acquired from experiment.
Using mean and std of prediction of X explortion space, the algorithm calculate which point seem to be optimized point.

The algorithm options are followings.

This notebook offer three options for next candidate suggestion.
1: Mutual information (MI)
2: Expected improvement(EI), 
3: Probability of improvement (PI) [0: Estimated y-values]