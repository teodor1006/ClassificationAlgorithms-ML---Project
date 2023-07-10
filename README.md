# ClassificationAlgorithms-ML---Project


Task: Diagnosing breast cancer
We have found patient data for breast cancer on the internet. Can we train a model that can make the diagnosis?

=> Source of the data: https://www.kaggle.com/uciml/breast-cancer-wisconsin-data

The goal is to predict the type of tumor (column: diagnosis). With a well-performing model, we could potentially save some surgeries or at least alleviate many concerns.

M: Malignant, malignant tumor
B: Benign, benign cancer
Task:

Train a model.
You cannot directly predict the diagnosis column. First, it needs to be converted into a column with 0 and 1 values.
Evaluate various classification models... which one works the best?
Note that you may need to scale the data for some models.
Make sure to set aside test data - only use it at the very end to determine accuracy on never-before-seen data.
Important: To make this meaningful, we can only assess accuracy on the test data after selecting the model (and tuning the parameters)!
The id column is likely not informative for our model. You should consider removing this column from the data.
Bonus questions:

For some models, PCA (Principal Component Analysis) might be worthwhile.
How many columns does the model actually need? Can it work with fewer columns? This would mean our doctor would need to measure and enter fewer values into the computer, saving valuable time!
