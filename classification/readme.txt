This directory contains all relevant code used for classifiying the datasets into samples with or without a pleateau:

-The code in "create_mockups.txt" was used to generate mockups of the original data.
-"load_testset.txt" is about loading the original samples into numpy arrays in order to calculate predictions (used as a testset).
-The "train" files define a tested model respectively.
-Since the creation of mockup samples was not sofisticated enough, "covnet_only_test.txt" trains a covnet on the original data using k-fold validation to investigate wether finding plateaus is possible at all.

