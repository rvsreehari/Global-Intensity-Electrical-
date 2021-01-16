Develop a Machine Learning model to predict the Global Intensity
Develop a Machine Learning model to predict if the Global Intensity is greater than 15.


Name of the Datasets : Household Power Consumption.
Dataset is a minute wise data logging of Power Consumption of a Household Consumption
Data Record Duration : December 2006 to November 2010 (4 Years).
Record Frequency : Per minute
Features recorded (07 No.) :
Global Active Power
Global Reactive Power
Voltage
Global Intensity
Sub metering 1
Sub metering 2
Sub metering 3
Observations : 2075259 (around 2 million)
 
 
 Data loading
 
Converting the original dataset from the raw txt file to csv format.
Slice out the bottom/latest 200,000 observations for Project tests, and carry on the experiments with other available data observations.
Crosscheck the discrepancies and abnormalities in the dataset, and amend for further usage.
Load the data from csv file into Pandas dataframe for further usage.

Data Analysis

In the prepared dataframe, checking the patterns of the different features using various reports and graphs
Checking the correlations among features
Checking the feature importance
Checking the missing values
Checking the outliers
Statistical Analysis

Data Cleaning

Dropping off the unnecessary or irrelevant features
Treatment of the values creating the imbalance of the data
Finding and treating the outliers wherever required
Finding and treating the missing values appropriately wherever required.

Data Transformation

Checking and Converting the features into needful formats.
Merging the relevant features as per requirements

Pre-processing

Prepare the data for modelling by using Train-Test split method
Pre-processed data must contain X_train, X_test, Y_train, Y_test dataframes

Modelling

Apply the relevant algorithms on the provided pre-processed data
Evaluate the accuracy of the model by using test data
Re-modelling to be done until the optimized results are achieved.
Re-modelling to be done using Algorithms changes and Hyper-parameter finetuning methods.

Results

Results of the machine learning to be drafted in the forms of Accuracy, Confusion Matrix, Classification reports wherever applied.

