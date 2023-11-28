# Deep-Learning

## Overview 
The nonprofit foundation Alphabet Soup wants a tool that can help it select the applicants for funding with the best chance of success in their ventures. With your knowledge of machine learning and neural networks, you’ll use the features in the provided dataset to create a binary classifier that can predict whether applicants will be successful if funded by Alphabet Soup.

From Alphabet Soup’s business team, we have received a CSV containing more than 34,000 organizations that have received funding from Alphabet Soup over the years. Within this dataset are a number of columns that capture metadata about each organization, such as:
- EIN and NAME—Identification columns
- APPLICATION_TYPE—Alphabet Soup application type
- AFFILIATION—Affiliated sector of industry
- CLASSIFICATION—Government organization classification
- USE_CASE—Use case for funding
- ORGANIZATION—Organization type
- STATUS—Active status
- INCOME_AMT—Income classification
- SPECIAL_CONSIDERATIONS—Special considerations for application
- ASK_AMT—Funding amount requested
- IS_SUCCESSFUL—Was the money used effectively

## Process
### Preprocess the Data :
Using our knowledge of Pandas and scikit-learn’s StandardScaler(), we’ll need to preprocess the dataset. This step prepares you for Step 2, where you'll compile, train, and evaluate the neural network model.
- Read in the charity_data.csv to a Pandas DataFrame
- drop the EIN and NAME columns
- Determine the number of unique values for each column.
 For columns that have more than 10 unique values, determine the number of data points for each unique value.
- Use the number of data points for each unique value to pick a cutoff point to bin "rare" categorical
- variables together in a new value, Other, and then check if the binning was successful.
- Use pd.get_dummies() to encode categorical variables.
- Split the preprocessed data into a features array, X, and a target array, y. Use these arrays and the train_test_split function to split the data into training and testing datasets.
- Scale the training and testing features datasets by creating a StandardScaler instance, fitting it to the training data, then using the transform function.
### Compile, Train, and Evaluate the Model : 

- Continue using the file in Google Colab in which you performed the preprocessing steps from Step 1.
- Create a neural network model by assigning the number of input features and nodes for each layer using TensorFlow and Keras.
- Create the first hidden layer and choose an appropriate activation function.
- If necessary, add a second hidden layer with an appropriate activation function.
- Create an output layer with an appropriate activation function.
- Check the structure of the model.
- Compile and train the model.
- Create a callback that saves the model's weights every five epochs.
- Evaluate the model using the test data to determine the loss and accuracy.
- Save and export your results to an HDF5 file. Name the file AlphabetSoupCharity.h5.

### Optimize the Model : 
Using our knowledge of TensorFlow, We're going to optimize the model to try to achieve a target predictive accuracy higher than 75%.
- Create a new Google Colab file and name it AlphabetSoupCharity_Optimization.ipynb.
- Import your dependencies and read in the charity_data.csv to a Pandas DataFrame.
- Preprocess the dataset as you did in Step 1. Be sure to adjust for any modifications that came out of optimizing the model.
- Design a neural network model, and be sure to adjust for modifications that will optimize the model to achieve higher than 75% accuracy.
- Save and export your results to an HDF5 file. Name the file AlphabetSoupCharity_Optimization.h5.

## Contact
If there are any questions of concerns, I can be reached at:
##### [github: MaiDao Lor](https://github.com/MaiDaoLor)
##### [email: mdl06@yahoo.com](mailto:mdl06@yahoo.com)
