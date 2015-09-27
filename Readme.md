## Gettings and Cleaning Data - Course Project

The R script, <code>run_analysis.R</code> does the following - 

- Downloads the dataset if it does not already exist in the working directory
- Loads the activity and feature info
- Loads both the training and test datasets, keeping only those columns which reflect a mean or standard deviation
- Loads the activity and subject data for each dataset, and merges those columns with the dataset
- Merges the train & test datasets
- Converts the <code>activity</code> and <code>subject</code> columns into factors
- Creates a tidy dataset that consists of the average (mean) value of each variable for each subject and activity pair.

The end result is present in the file <code>tidy.txt</code>.

