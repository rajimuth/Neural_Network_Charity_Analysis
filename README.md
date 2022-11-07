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
- 

