# Decision-Tree-Modeling
Decision tree modelling using R

The following sample datasets are provided with the R package rpart:
- kyphosis
- solder

For both of these I have performed the following analysis:
1. Create a model using the rpart function.
2. Create a nice decision tree plot.
3. List the important attributes.
4. Using the best pruning parameter, create a pruned tree.
5. Divide the dataset into two parts:
training dataset using a random sample of 80% of the data - test dataset using the remaining 20% of the data.
Build a pruned model using just the training dataset and use it to find the prediction on the test dataset. How much is the accuracy obtained.
6. Repeat step 5, but this time use 90% of the data for training and the remaining 10% for testing. What is the new accuracy.
