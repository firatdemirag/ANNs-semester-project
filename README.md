# ANNs Semester Project

This repository contains the code for a semester project on churn prediction using artificial neural networks (ANNs). The aim of this project is to build an ANNs model that can predict whether a customer is likely to churn (i.e., stop using a product or service).

### Data
The dataset used in this project is the "Telco Customer Churn" dataset, which can be found on [Kaggle](https://www.kaggle.com/datasets/blastchar/telco-customer-churn). The dataset contains information about customers of a telecom company and whether they have churned or not. The features include demographic information, services used, and monthly charges.

### Model
We have used a three-layer feedforward neural network with 10 neurons in the input layer, 10 neurons in the hidden layer, and 1 neuron in the output layer. The input features are normalized using MinMaxScaler, and the model is trained using the Adam optimizer and binary cross-entropy loss. The code for the model can be found in the `churn_prediction.ipynb` notebook.

### Results
The trained model achieved an accuracy of 81.2% on the test set, with a precision of 71.8%, recall of 56.6%, and an F1 score of 63.3%. These results suggest that the model is effective at predicting churn and can be used to identify customers who are at risk of churning.

### How to Use
To use this project, simply clone this repository and run the `churn_prediction.ipynb` notebook. The notebook contains all the code required to train the model and make predictions on new data. You can also modify the code to experiment with different model architectures and hyperparameters.

### Contributors
This project was developed by [Firat Demirag](https://github.com/firatdemirag) as part of a semester project. Contributions are welcome, and please feel free to open an issue if you have any questions or suggestions.
