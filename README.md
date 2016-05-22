# run_analysis README

The run_analysis.R file, provided that getdata_projectfiles_UCI HAR Dataset folder is 
located (and unzipped) in the working directory, does the following:

* Merges the training and the test sets to create one data set, named total_data. The data set contains two more colums, corresponding to the activity and the subject. This information is taken from files y_test.txt, subject_test.txt, y_train.txt and subject_train.txt contained in the original folder getdata_projectfiles_UCI HAR Dataset.
* Uses descriptive activity names to name the activities in the data set
* Appropriately labels the data set with the (descriptive) variable names contained in file features.txt in the original folder getdata_projectfiles_UCI HAR Dataset.
* From the comprehensive data set total_data it extracts only the measurements on the mean and standard deviation for each measurement, and forms the data set data_comp.
* Finally, from the data set data_comp it creates the data set data_mean that containes the average of each variable for each activity and each subject.
