## Venture Funding with Deep Learning

This Jupyter notebook is designed to be uploaded and run on Google Colab. It covers the following steps:

## Data Preparation

1. Read the `applicants_data.csv` file into a Pandas DataFrame.
2. Drop the "EIN" and "NAME" columns.
3. Encode categorical variables using `OneHotEncoder`.
4. Add numerical variables from the original DataFrame to the encoded DataFrame.
5. Create features (`X`) and target (`y`) datasets.
6. Split data into training and testing sets.
7. Scale features data using `StandardScaler`.

## Compile and Evaluate a Binary Classification Model

1. Create a deep neural network with input features, layers, and neurons.
2. Compile and fit the model using binary cross-entropy loss, adam optimizer, and accuracy metric.
3. Evaluate the model on test data.
4. Save the model as an HDF5 file named `AlphabetSoup.h5`.

## Optimize the Neural Network Model

1. Define at least three new deep neural network models as optimization attempts.
2. Display and compare the accuracy scores of all models.
3. Save each alternative model as an HDF5 file.