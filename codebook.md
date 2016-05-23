#codebook of run_analysis.R

The variables of the data set data_mean, which is the basic output of this script, are named as the original variables contained in file features.txt contained in the original folder getdata_projectfiles_UCI HAR Dataset. 

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
                         fBodyGyro-std()-Y
                         fBodyGyro-std()-Z
                         fBodyAccMag-mean()
                         fBodyAccMag-std()
                         fBodyBodyAccJerkMag-mean()
                         fBodyBodyAccJerkMag-std()
                         fBodyBodyGyroMag-mean()
                         fBodyBodyGyroMag-std()
                         fBodyBodyGyroJerkMag-mean()
                         fBodyBodyGyroJerkMag-std()
                         
  They correspond to the average values of the original values for each subject and activity.
  
Finally, the data set contains two more variables:
                        activity: which take tha values "walking", "walking_upstairs", "walking_downstairs", "sitting", "standing", "laying"
                        
                        subject: the number of the subject. Takes values from 1 to 30