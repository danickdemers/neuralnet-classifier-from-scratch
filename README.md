# Neural Net Classifier from scratch

 This is a manual implementation of a neural net classifier from scratch with **back-propagation**. Inspired from the pseudo-code provided in **section 18.7 of Artificial Intelligence - A Modern Approach** by Russel and Norvig. In this 
## Dependencies
- Python
- Numpy
- Sklearn

## Files
- **metrics**: Manual implementation of confusion matrix. Prints important metrics such as accuracy, precision, recall and f1 score.
- **main**: Execution file. Execute it with your python env.
- **single_hlayer_nn**: One hidden layer neural network. 3 layers: one for input, one hidden and one for output.
- **multi_hlayer_nn**: Multiple hidden layer neural network. All the hidden layers are the same size.
- **custom_hlayer_nn**: Custom hidden layer neural network. Much like SkLearn, it use a tuple to determine the layout of the neural network. Here is an example for a custom network of 3 hidden layers with 5, 6 and 7 neurons: (5, 6, 7).
- **load_datasets**: Load the datasets for the neural net.
- **hyperparams**: Use k-fold to find the best hyperparameters for the datasets.
