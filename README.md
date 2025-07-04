# ClinVarPredictionModel

This project is an exercise in building ensemble models using multiple methods and handling noisy data. The goal was to improve performance of the model, as measured by F score, compared to the work done on kaggle.
A common problem the Kaggle submissions failed to address was overfit of data and bias due to class imbalance.

Using a multilayer heterogenous ensemble model and robust data shaping and cleaning to cut through noise, I was able to take the dataset below and outperform all submissions by the proposed metric.

To note, while it is generally best to prepare datasets based on the model being applied (for example leaving outliers in place for decision tree algorithms), in this case the same dataset was used for all three. The decision was made
after comparing results using multiple shaped datasets, and a singular one. The singular dataset with outliers and NA imputed outperformed the "correct" approach by a wide margin. I would argue that this was the case due to the noise of the dataset.

### Original Dataset
Data Storage for Clinvar dataset found [here](https://www.kaggle.com/datasets/kevinarvai/clinvar-conflicting) to permit direct download in R notebook.
