# CodeBook

## Data Source
Human Activity Recognition Using Smartphones Dataset  
[UCI HAR Dataset](https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip)

## Variables
- **subject**: Identifier of the subject (ranges from 1 to 30).
- **activity**: Descriptive activity name (e.g., WALKING, SITTING, LAYING).
- **measurements**: Selected features representing mean and standard deviation values from accelerometer and gyroscope signals.

## Transformations
1. **Merged datasets**: Combined training and test sets into one unified dataset.
2. **Feature extraction**: Retained only measurements on the mean and standard deviation for each signal.
3. **Activity labeling**: Replaced numeric activity codes with descriptive activity names.
4. **Variable renaming**: Cleaned and standardized variable names:
   - `Acc` → `Accelerometer`
   - `Gyro` → `Gyroscope`
   - `Mag` → `Magnitude`
   - Prefix `t` → `Time`
   - Prefix `f` → `Frequency`
   - Removed duplicates (`BodyBody` → `Body`)
5. **Tidy dataset creation**: Produced a final dataset with averages of each variable grouped by subject and activity
