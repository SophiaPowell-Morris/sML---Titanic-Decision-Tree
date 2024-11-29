# sML---Titanic-Decision-Trees & Ensemble Methods (Bagging, Bootstrapping, Boosting)

Created a Decision Tree that could predict the survival of passengers on the Titanic. (Note: No estrictions were imnposed on the depth of the tree.)

After the data was loaded into the notebook, the relevant variables were selected from the dataset and then split into a training, development, and testing sets. 

A decision tree was trained using the training set, with an accompaning plot. 

The accuracy of the model on the development set was computed. 

Tree pruning was performed on both the training and development sets using the maxdepth parameter set in the range 2-10, inwhich a plot and accuracy score was computed for each max_depth value.

A plot containing the training accuracies and development accuracies was generated, and the results examined the explained based on the shape of the lines plotted. 

An optimum max_depth value was picked, and an final DC was trained using this parameter. 

The accuracy of the final model on the test data was reported and interpreted.
