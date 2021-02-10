# credit_scoring

## Overview

1. Loading Data
- Splitting input and outputs
- Plotting numerical features
2. Preprocessing Data
- Converting Y/N to binary
- Deleting mostly null columns and fill the remaining columns
- One-hot encoding the categorical variables
- Normalize data
- Delete columns which has low correlation with target
- Delete half of the columns which has high correlation between other features
- Oversample the minority class (class 1)
3. Selecting Features
- Selecting most 10 important features with pre-build libraries
- Split data to train and test
- Plot the importance of features
- Find and plot the best weights for models using GridSearch
4. Training and Testing
- Train multiple models
- Compare model results using Confusion Matrix, F1 score and AUC
- Plot each models recall and precision for visual results
