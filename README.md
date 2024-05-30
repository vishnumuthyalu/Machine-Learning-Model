# Machine-Learning-Model
 - This code implements a machine learning model using the ID3 decision tree algorithm an Stochastic Gradient Descent algorithm
 - It reads, preprocesses data, trains a model, and evaluates its performance

# Stochastic Gradient Descent Algorithm 
- The Stochastic Gradient Descent is an optimization algorithm used to minimize the loss function during training
- The SGD section of this code uses an Activation Function (Sigmoid) in order to implement the Perceptron algorithm for training the model using the training datasets
- After the model has been trained, the code will then test the model using the weights from the train function
- In the SGD function the the trainFunction anf TestFunction are called and the accuracies for both are returned
- The Accuracy Plots for training and testing are displayed

# ID3 Decision Tree Algorithm 
- The ID3 Algorithm is used to construct a decision tree by selecting attributes based on information gain and entropy
- The ID3 section of this code uses an Entropy Function to calulate the measure of impurity in the dataset.
- The ID3 section of this code uses an informationGain function to calculate the information gain using the total entropy and unique subset entropy for a given feature from the dataset
- The ID3 section of this code uses a maximumGain function to find the feature in the dataset with the maximum gain
- The ID3 section of this code uses a majorityLabel function that finds the class label in the data set with the most occurences
- The section of code also contains user defined functions for the ID3 implementation ( recursive), and printing the tree
- After the decision tree has been made the, a predictInstance function is used ot predict instances based on the decision tree, and finally a calculateAccuracy funtion calculates the accuracy of the decision tree for the dataset
- This is done for both the Training and Testing Data Sets

# Datasets Used
- gd-train.dat and gd-test.dat used for SGD Algorithm 
- id3-train.dat and id3-test.dat used for ID3 Algorithm

# To Test Code 
- download .ipynb file , and download the four .dat files : gd-train.dat, gd-test.dat, id3-train.dat, and id3-test.dat
- in source code , change the file path, by modifying the basePath variable. The modification should point to a folder that holds the four .dat files, so that they can be accessed by the code
- basePath = "your_file_path"
- You will now be able to test out the code 



