# Cars MPG Regression

![cars mgp](https://images.cars.com/cldstatic/wp-content/uploads/best-car-mileage-for-2022-scaled.jpg)

## Dataset Information

This dataset is a modified version of the dataset from the StatLib library, used for predicting city-cycle fuel consumption in miles per gallon ("mpg") based on various attributes. The original dataset contained 8 instances with unknown "mpg" values, and they were removed.

## Importing Libraries

- `numpy`
- `pandas`
- `matplotlib.pyplot`
- `seaborn`
- `sklearn.preprocessing.LabelEncoder`
- `missingno`
- `warnings`
- `os`
- `plotly.express`

## Loading the Dataset

The dataset is read from a CSV file and stored in a Pandas DataFrame.

## Inspecting the Data

- Display the first 5 rows of the dataset.
- Display the last 5 rows of the dataset.

## Exploring the Data

- The dataset has 398 rows and 9 columns.
- Summary information about the dataset is provided, including data types, the number of unique values, and the count of missing values for each column.

## Discovering Missing Values

- Check for missing values in the dataset.
- Handle missing values in the "horsepower" column by replacing "?" with NaN and converting the data type to float.
- Check for missing values again.

## Modeling Part

- Import `Keras` library.
- Define the model for regression using a neural network.

## Data Preparation

- Split the dataset into training and test sets.
- Standardize the input features using `StandardScaler`.

## Defining the Model

- Define a neural network model using `Keras` with three layers (30 units, 20 units, and 1 unit).

## Training the Model

- Compile the model with mean squared error (MSE) as the loss function and RMSprop optimizer.
- Train the model for 100 epochs.
