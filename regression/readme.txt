This directory contains all relevant code used in searching for plateaus. Here the transfer from fake to original data functions reasonably well:

-The code in "create_mockups.txt" was used to generate mockups of the original data.
-"load_testset.txt" is about loading the original samples into numpy arrays in order to calculate predictions (used as a testset).
-"split_branches.txt" trains a model where the evaluation of plateau start and end is completly independent.
-"shared_branches.txt" also uses two different covnets for start and end but the results get concatenated.
