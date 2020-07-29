# Handwritten Digit Recognition using MNIST dataset

#### (I) Steps followed for processing and digit recognition:
1. MNIST dataset is taken from keras directly
2. These numerical digits are written by hand from 0 to 9.
3. Simple Neural network is built to recognising these numerical digits
4. Set of best hyperparameters is derived by performing grid search cross validation.

#### (II) Result:
1. Neural netowrk perfornamce = 97.27%
2. Hyperparameter tuning (using GridSearch) performance = 97.52%
3. Hyperparameter tuning + Dropout layers performance = 97.81%

***There was not much of improvement as compared to 1st model hence keeping 1st model for prediction***

#### (III) Future Tasks:
1. Using CNN to improve the accuracy
2. Compare the performance of NN and CNN
