# Neural_Network_Charity_Analysis
Neural Network Binary Classification to predict credible applicants for a Philanthropic organization

Domain : Neural Network

Techniques : Tensorflow, Keras library, Sequence model, Standard scaler, One Hot encoder

Application : Funding analysis

### Purpose of the Analysis
The purpose of the analysis is to help a foundation predict where to make investments. Features in the dataset will be used to create a Binary Classifier that is capable of predicting whether applicants will be successful if funded by the organization. Feautures in the dataset include Name and EIN of the applicants, Application Type, Affiliation, Classification, Use case for funding, Organization type, Status, Income classification, Special Considerations, Asking Funsing Amount and if the money was used effectively.

### Data Pre Processing
- Read data to a Panda DataFrame
- Identify Target and features of the model
- Dropping columns not needed
- Determine the unique values for each column
- Create density plot to determine the distribution of the column values
- Bin together rare catrgorial variable together in a new column "other"
- Generate a list of categorial variables
- Encode categorical variables using one-hot encoding
- Place encoded variables in a new dataframe
- Merge one-hot encoding Dataframe with the original dataframe and drop the originals

### Compile, Train, and Evaluate the Model
- Neural network model by designed by assigning the number of input features and nodes for each layer using Tensorflow Keras.
- Assigned RELU activation function for first and second hidden layers
- Assigned Sigmoid activation function for the output layer
- Compiled and trained the model
- The model was evaluated using the test data to determine the loss and accuracy

<img width="323" alt="image" src="https://user-images.githubusercontent.com/94877067/200393973-b2ede378-86fa-4d2c-ae8d-d511e342bec3.png">

### Summary

- Optimization with multiple layers, scaled data, different noder per layer gave loss of 0.55 and 72% accuracy.
- With less than 72% accuracy, other machine learning models need to be analyzed for a fairly reliable classifier
- Future analysis will aim at applying Random Forest Model as they can perform at similar capacity as Neural Network but cam handle input data differently to predict the classification

