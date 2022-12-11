# Leaf-Classification
1. In this project, you will use the Leaf Classification dataset using a neural 
network architecture. 
1) First, download the data file, load it
1. Describe the data
2. Clean the data 
3. Check the data for missing values or duplicates and carry out proper correction 
methods
4. Visualize the data using proper visualization methods. 
5. Draw some of the images 
6. Carry out required correlation analysis
7) divide the data into a training and test set using approximately 80% for training.  
8) Encode the labels
Part II: Training a neural network
You also need to write the training function (training), and should explore the following 
hyperparameter settings: 
• Batch size: Number of examples per training iteration. 
• Hidden size: Try using different number of hidden nodes in your model and compare the 
performances. 
• Dropout is an effective strategy to defend against overfitting. Adding a dropout layer 
after the hidden layer, and try using different dropout rate to compare the performances. 
• Optimizer: Try using different optimizers such as SGD, Adam, RMSProp,Adagrad . 
• Regularization (weight decay): L2 regularization can be specified by setting the 
weight_decay parameter in optimizer. Try using different regularization factor and check 
the performance.
#Hyperparamter tunning by KerasTuner with TensorBoard

