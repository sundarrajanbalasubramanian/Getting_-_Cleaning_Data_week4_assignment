**README**

**Assignment: Getting and Cleaning Data Course Project**

This repository is for Getting and Cleaning Data course project assignment submitted by Sundar Rajan Balasubramanian. 
This has the instructions on how to run analysis on Human Activity recognition dataset.

**Dataset**

Human Activity Recognition (HAR) Using Smartphones. Get the HAR.zip file from the course assigned UCI database cloud and unzip it for further use.

**Files**

CodeBook.md a code book that describes the variables, the data, and any transformations or work that I performed to clean up the data

run_analysis.R contains the code for cleaning of the datset. 
It starts from loading the required library packages and calling the dataset.
It is then followed by the steps required as described in the course project’s definition:
1. Merge the training and the test sets to create one data set.
2. Extract only the measurements on the mean and standard deviation for each measurement.
3. Use descriptive activity names to name the activities in the data set
4. Appropriately label the data set with descriptive variable names.
5. Create a second, independent tidy data set with the average of each variable for each activity and each subject.

FinalData.txt is the output final data after running all the sequences described above.
