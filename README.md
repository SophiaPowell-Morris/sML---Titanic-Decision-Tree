# sML---Titanic-Decision-Tree

Create a Decision Tree that can predict the survival of passengers on the
Titanic. Make sure not to impose any restrictions on the depth of the tree.

Load the titanic.csv dataset into a Jupyter notebook. This dataset comes
from here.

Select relevant variables from the data and split the data into a training,
development, and test set.

Train a decision tree and make a plot of it.

Compute your model’s accuracy on the development set.

For tree pruning in Sklearn we usually use the maxdepth parameter, a
parameter which determines how many levels the tree can have. Try
building your model with different values of the max_depth [2-10]. At each
step, create a plot of your tree and store the accuracies on both the training
and development data.

Plot a line of your training accuracies and another of your development
accuracies in the same graph. Write down what shape the lines have and
what this shape means.

Pick an optimum value for the max_depth parameter and train your final
decision tree using this parameter

Report the accuracy of your final model on the test data.
