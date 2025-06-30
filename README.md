# DECISION-TREE-IMPLEMENTATION

*COMPANY*: CODTECH IT SOLUTIONS

*NAME*: NISHANT KODAN

*DOMAIN*: MACHINE LEARNING

*DURATION*: 4 WEEKS

*MENTOR*: NEELA SANTOSH

*OUTPUT*:

Number of samples in training set: 105

Number of samples in testing set: 45

Decision Tree model trained successfully!

Accuracy of the model on the test set: 1.00

![Image](https://github.com/user-attachments/assets/6b71996b-13c7-4e31-8dab-08d92c9b5963)

Feature Importances:

petal length (cm): 0.9251

petal width (cm): 0.0749

sepal width (cm): 0.0000

sepal length (cm): 0.0000

![Image](https://github.com/user-attachments/assets/dc8a9cf3-d320-4e33-b50a-b9463064c18d)

--- Basic Analysis ---

The plot above shows the decision tree.
 
- Each box (node) shows a condition (e.g., 'petal width (cm) <= 0.8').
 
- If the condition is true, you go left; if false, you go right.
 
- 'samples' tells you how many data points reached that node.
 
- 'value' shows how many samples belong to each class [setosa, versicolor, virginica] at that node.
 
- 'class' is the predicted class for samples reaching that node.
 
- Leaf nodes (nodes at the bottom with no further splits) are the final predictions.

The model predicted with an accuracy of 100.00% on the unseen test data.

The 'Feature Importances' bar graph shows which measurements the tree used most to make decisions.

A higher bar means that feature was more important for the classification.
