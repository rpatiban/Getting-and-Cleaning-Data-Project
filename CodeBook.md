##run_analysis.R performs the below steps.

	* Merges the training and the test sets to create one data set.
	* Extracts only the measurements on the mean and standard deviation for each measurement.
	* Uses descriptive activity names to name the activities in the data set
	* Appropriately labels the data set with descriptive activity names.
	* Creates a second, independent tidy data set with the average of each variable for each activity and each subject.

##How run_analysis.R implements :

	* Require reshapre2 and data.table librareis.
	* Load both test and train data.  
	* Intutive names for all the variables are used to represent both test and train datasets respectively
	* Load the features and activity labels.
	* Extract the mean and standard deviation column names and data.
	* Process the data. There are two parts processing test and train data respectively.
	* Merge data set.
