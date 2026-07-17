# GettingDataProject
# Getting and Cleaning Data Project

## Overview
This project demonstrates the ability to collect, work with, and clean a dataset.  
The goal is to prepare tidy data that can be used for later analysis.  
The dataset originates from accelerometers on Samsung Galaxy S smartphones and is available from the UCI Machine Learning Repository.

## Files in this repository
- `run_analysis.R`: R script that performs the data cleaning and transformation.
- `CodeBook.md`: Describes variables, data, and transformations applied.
- `FinalData.txt`: The tidy dataset output.
- `README.md`: Explains the project and how the scripts work together.

## How to run
1. Download and unzip the dataset from the following link:  
   [UCI HAR Dataset](https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip)
2. Place the `UCI HAR Dataset` folder in your working directory.
3. Run the script:
   ```r
   source("run_analysis.R")
