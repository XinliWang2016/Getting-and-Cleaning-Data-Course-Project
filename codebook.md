## Data Manipulation 
1. Merges the training and the test sets to create one data set.
2. Extracts only the measurements on the mean and standard deviation for each measurement.
3. Uses descriptive activity names to name the activities in the data set
4. Appropriately labels the data set with descriptive variable names.
5. From the data set in step 4, creates a second, independent tidy data set with the average of each variable for each activity and each subject.

## Output
* For step 4, the cleaned data set is saved in `tidy data.txt`. For step 5, the cleaned data set is saved in `tidy data with average.txt` 

* variables in `tidy data.txt` are: 
``` activity
    tBodyAcc-mean()-X
    tBodyAcc-mean()-Y
    tBodyAcc-mean()-Z
    tBodyAcc-std()-X
    tBodyAcc-std()-Y
    tBodyAcc-std()-Z
    tGravityAcc-mean()-X
    tGravityAcc-mean()-Y
    tGravityAcc-mean()-Z
    tGravityAcc-std()-X
    tGravityAcc-std()-Y
    tGravityAcc-std()-Z
    tBodyAccJerk-mean()-X
    tBodyAccJerk-mean()-Y
    tBodyAccJerk-mean()-Z
    tBodyAccJerk-std()-X
    tBodyAccJerk-std()-Y
    tBodyAccJerk-std()-Z
    tBodyGyro-mean()-X
    tBodyGyro-mean()-Y
    tBodyGyro-mean()-Z
    tBodyGyro-std()-X
    tBodyGyro-std()-Y
    tBodyGyro-std()-Z
    tBodyGyroJerk-mean()-X
    tBodyGyroJerk-mean()-Y
    tBodyGyroJerk-mean()-Z
    tBodyGyroJerk-std()-X
    tBodyGyroJerk-std()-Y
    tBodyGyroJerk-std()-Z
    tBodyAccMag-mean()
    tBodyAccMag-std()
    tGravityAccMag-mean()
    tGravityAccMag-std()
    tBodyAccJerkMag-mean()
    tBodyAccJerkMag-std()
    tBodyGyroMag-mean()
    tBodyGyroMag-std()
    tBodyGyroJerkMag-mean()
    tBodyGyroJerkMag-std()
    fBodyAcc-mean()-X
    fBodyAcc-mean()-Y
    fBodyAcc-mean()-Z
    fBodyAcc-std()-X
    fBodyAcc-std()-Y
    fBodyAcc-std()-Z
    fBodyAccJerk-mean()-X
    fBodyAccJerk-mean()-Y
    fBodyAccJerk-mean()-Z
    fBodyAccJerk-std()-X
    fBodyAccJerk-std()-Y
    fBodyAccJerk-std()-Z
    fBodyGyro-mean()-X
    fBodyGyro-mean()-Y
    fBodyGyro-mean()-Z
    fBodyGyro-std()-X
```
* variables in `tidy data with average.txt` are:

``` subject
    activity
    tBodyAcc-mean()-X
    tBodyAcc-mean()-Y
    tBodyAcc-mean()-Z
    tBodyAcc-std()-X
    tBodyAcc-std()-Y
    tBodyAcc-std()-Z
    tGravityAcc-mean()-X
    tGravityAcc-mean()-Y
    tGravityAcc-mean()-Z
    tGravityAcc-std()-X
    tGravityAcc-std()-Y
    tGravityAcc-std()-Z
    tBodyAccJerk-mean()-X
    tBodyAccJerk-mean()-Y
    tBodyAccJerk-mean()-Z
    tBodyAccJerk-std()-X
    tBodyAccJerk-std()-Y
    tBodyAccJerk-std()-Z
    tBodyGyro-mean()-X
    tBodyGyro-mean()-Y
    tBodyGyro-mean()-Z
    tBodyGyro-std()-X
    tBodyGyro-std()-Y
    tBodyGyro-std()-Z
    tBodyGyroJerk-mean()-X
    tBodyGyroJerk-mean()-Y
    tBodyGyroJerk-mean()-Z
    tBodyGyroJerk-std()-X
    tBodyGyroJerk-std()-Y
    tBodyGyroJerk-std()-Z
    tBodyAccMag-mean()
    tBodyAccMag-std()
    tGravityAccMag-mean()
    tGravityAccMag-std()
    tBodyAccJerkMag-mean()
    tBodyAccJerkMag-std()
    tBodyGyroMag-mean()
    tBodyGyroMag-std()
    tBodyGyroJerkMag-mean()
    tBodyGyroJerkMag-std()
    fBodyAcc-mean()-X
    fBodyAcc-mean()-Y
    fBodyAcc-mean()-Z
    fBodyAcc-std()-X
    fBodyAcc-std()-Y
    fBodyAcc-std()-Z
    fBodyAccJerk-mean()-X
    fBodyAccJerk-mean()-Y
    fBodyAccJerk-mean()-Z
    fBodyAccJerk-std()-X
    fBodyAccJerk-std()-Y
    fBodyAccJerk-std()-Z
    fBodyGyro-mean()-X
    fBodyGyro-mean()-Y
    fBodyGyro-mean()-Z
    fBodyGyro-std()-X
```
