# Data Classification of MAGIC gamma telescope data
Using the MAGIC telescope data, we will try to classify the data into gamma and hadron classes. The data is available at [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/MAGIC+Gamma+Telescope).
We use the following machine learning algorithms:
* Decision Trees
* Naive Bayes Classifier
* Random Forests
* AdaBoost  
* K-NN

We also use a neural network to classify the data.

## Data
The data was balanced by oversampling the majority class (gamma) to match the minority class (hadron). The data was split into training and testing sets with a ratio of 70:30, and cross-validation was used to tune the hyperparameters of the models.

## The Notebooks
* [Classification Algorithms](./Classification_Algorithms.ipynb)
* [Neural Network](./NeuralNetwork.ipynb)

## Authors
- Haguar Tarek
- Manar Amgad
- Mariem Mostafa
- Nada Elwazane