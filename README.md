## Peer-graded Assignment: Getting and Cleaning Data Course Project
# This repo contains the required submission for coursera Getting and Cleaning Data week4 project, it's contain:
* README.md file.
* CodeBook.md
* datasetordered.txt
* script.R

# Experiment: 
The experiments have been carried out with a group of 30 volunteers within an age bracket of 19-48 years. Each person performed six activities (WALKING, WALKING_UPSTAIRS, WALKING_DOWNSTAIRS, SITTING, STANDING, LAYING) wearing a smartphone (Samsung Galaxy S II) on the waist. Using its embedded accelerometer and gyroscope, we captured 3-axial linear acceleration and 3-axial angular velocity at a constant rate of 50Hz. The experiments have been video-recorded to label the data manually. The obtained dataset has been randomly partitioned into two sets, where 70% of the volunteers was selected for generating the training data and 30% the test data. 
The sensor signals (accelerometer and gyroscope) were pre-processed by applying noise filters and then sampled in fixed-width sliding windows of 2.56 sec and 50% overlap (128 readings/window). The sensor acceleration signal, which has gravitational and body motion components, was separated using a Butterworth low-pass filter into body acceleration and gravity. The gravitational force is assumed to have only low frequency components, therefore a filter with 0.3 Hz cutoff frequency was used. From each window, a vector of features was obtained by calculating variables from the time and frequency domain. See 'features_info.txt' for more details. 

# CodeBook.md file:
contains data that's indicate all the variables and summaries calculated, along with units, and any other relevant information.

# datasetordered.txt:
This file contain the tidy processed data in which average of each variable for each activity and each subject was calculated.

# run_analysis.R:
In which a code to reproduce the tidydata set is included. 

R script c that does the following.

    Merges the training and the test sets to create one data set.
    Extracts only the measurements on the mean and standard deviation for each measurement.
    Uses descriptive activity names to name the activities in the data set
    Appropriately labels the data set with descriptive variable names.
    From the data set in step 4, creates a second, independent tidy data set with the average of each variable for each activity     and each subject.
