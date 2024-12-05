For this project, we have created a multiclass classifier to classify stars into 6 classes (0,1,2,3,4,5). Where Brown Dwarf = 0, Red Dwarf = 1, White Dwarf = 2, 
Main Sequence = 3, Supergiant = 4, HyperGiant = 5. 

To run this code, please just go through the notebook running each cell. The data for this project was preprocessed. For preprocessing, we standardized string names of Star color, 
we checked correlations of each feature with star type, used one hot encoding to encode categorical features, added a log luminosity feature to the data set, and did robust scaling
for each feature. 

We used two models for this classification project: Decision Trees and Random Forest. For decision trees we used grid search to find the best hyperparameters. 
The decision tree was able to find an accuracy of 51.06%, while the random forest was able to find an accuracy of 76.60%
