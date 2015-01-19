# data-science-project1

Q: Where is the data from?

Data is downloaded from webpage:
http://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones

Direct link for the data for this project is:
https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip 

Q: How big is the data sets?

296M

Q: What is the data about?

30 people (variable name: subjectID) taking 6 activities (activities), measured by accelerometer and gyroscope. Each record lists out 561 variables including means, standard deviation, median....of the measured signals (for details , see feature.txt).

Training data set 70%
Testing data set 30%

Q: What does the program do to the data?

1. Merges the training and the test sets to create one data set.
2. Uses descriptive activity names to name the activities in the data set (ex, 'Walking' and 'Walking_Upstairs' instead of 1 and 2)
3. Extracts only the measurements on the mean and standard deviation for each measurement. (Only means and standard deviation of measurements are extracted, angle(....mean) is not included)
4. Appropriately labels the data set with descriptive variable names. (Make it R leagal, (), -, etc are illegal in variable names)
5. From the data set in step 4, creates a second, independent tidy data set with the average of each variable for each activity and each subjectID.

Q: What is the output of the program?

Two data sets are saved, as a result.

1. It saves the data set, extracted to contain only measurements on the mean and standard deviation for each measurement. Filename: './extract.txt'
2. It saves the data set, extracted to calculate average of each variable in './extract.txt' for each activity and each sujectID. Filename: './mean.txt'


