Fraudulent Payment Detection using Neural Networks
Description:
This project aims to develop a model capable of accurately detecting fraudulent payments from the provided log. The dataset is used for training, validating, and testing the models to achieve the most precise accuracy.

What I had done:
Data Preprocessing:

Load and explore the dataset.

Exploratory Data Analysis.

Data Visualization.

Train-Test Split:

Split the dataset into train, validate, and test sets (4,072,076 train examples, 1,018,020 validation examples, 1,272,524 test examples).

Model Training (after data pipelining):

Single Neural Network

Multi-input Neural Network.

Recurrent Neural Network (LSTM Model).

Evaluation:

Assess model performance on the test set.

Analyze and interpret the results.

Models used:
Single-input Neural Network Model:
Only one input layer is used to process the data. All features are combined into a single input layer (feature_layer), which is then fed into the sequential model. This approach is suitable when all features are of the same type and have a similar representation in the network.

Multi-input Neural Network Model:
Utilizes multiple input layers to handle different types of data. Each input layer processes a specific type of data or feature. The outputs of these input layers are then combined or merged before passing through the sequential model. This approach is beneficial when dealing with heterogeneous data types or when different features require different preprocessing steps.

Recurrent Neural Network (Long Short-Term Memory Model):
Particularly effective for tasks involving sequential data, where the model needs to remember information from previous time steps or tokens.

Libraries needed:
pandas

numpy

matplotlib

scikit-learn

tensorflow

keras

Visualizations:
Correlation Matrix

Count of all types of transactions

Count of frauds

Number of transactions by Type of transaction and isFlaggedFraud

Number of transactions by Type of transaction and isFraud

Conclusion:
After training and testing the model, the accuracies we got are up to 99.93% (yet at first epochs, can do for more epochs but a lot of time is required).

Accuracy Table: (Implicitly, a table would be here showing accuracies)

Contributor:
Name: Titiksha Agrawal

LinkedIn: https://www.linkedin.com/in/titiksha-agrawal-056004251/

GitHub: https://github.com/AgrawalTitiksha
