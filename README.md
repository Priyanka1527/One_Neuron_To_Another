# Says One Neuron To Another

#### Neural network architectures
1. Set up a new git repository in your GitHub account
2. Pick two datasets from https://en.wikipedia.org/wiki/List_of_datasets_for_machine-learning_research
3. Choose a programming language (Python, C/C++, Java)
4. Formulate ideas on how neural networks can be used to accomplish the task for the specific dataset
5. Build a neural network to model the prediction process programmatically
6. Document your process and results
7. Commit your source code, documentation and other supporting files to the git repository in GitHub

----------------------------------------------------------------------------------------------------
#### Data sets : Iris and Ecoli

- Iris : The Iris flower data set is a multivariate data set having a set of 150 records under five attributes - petal length, petal width, sepal length, sepal width and species. More details can be found in the respective notebook.

- Ecoli: This data set contains information of Escherichia coli. It is a bacterium of the genus Escherichia that is commonly found in the lower intestine of warm-blooded organism. More details have been mentioned in the respective notebook.


#### Usage of neural network:

Neural networks are a set of algorithms, modeled loosely after the human brain, that are designed to recognize patterns. In case of the data sets chosen in this assignment neural network can be used to perform classification of the flower species and protein class for Iris and Ecoli data sets respectively. Neural network can be used to help group unlabeled data according to similarities among the example inputs, and then classify data when it has a labeled dataset to train on.


#### Implementation: (**_"Neural Network - Iris.ipynb"_** is self contained with all the documentations, source code and notes)

All the implementation details along with the source code and results are documented in the notebook **"Neural Network - Iris.ipynb"**. The different stages of implementation have been discussed in details. The another notebook for Ecoli data set followed the exact same approach and hence not documented again over there.


#### Observations:

We could see that the number of iterations to train the network differed in both cases. The network was trained for over 500 iterations in case of Ecoli data set whereas Iris data set gave good results after 100 iterations. We also noticed the effect of overfitting once increased the training iterations in terms of accuracy. In the end, we achieved ~98% accuracy of predictions for Iris data set and ~89% accuracy of predictions for Ecoli data set. The predictions were checked against Test data set and one sample prediction was printed out for each of the data sets.
