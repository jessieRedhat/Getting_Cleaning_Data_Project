# Getting_Cleaning_Data_Project
It is the Getting and Cleaning Data Course Project which is required to be published in github. A tidy data set is the output of this project and, relative R code is writen in *run_analysis.R* file to produce the output. This code does the followings: 

* Download the source files and unzip it
* Load the activity and feature info, and merge activity codes with their names
* load and transpose features.txt to specify the headers for training and test datastes
* load other datasets of training and naming columns by their order in time window
* merge features, subjects, and features columns
* do the same for test data set
* merge training and test data sets to create *LargeDS* which is the whole dataset
* extract only columns from features which has only __mean__ or __std__ in the header, put it in *ExtracedDS*
* group the extracted dataset by 1) subject and 2) activity
* produce average value in each columns for each pair subject and activity, put it in **tidyDS**.

Other files in the repo:
1- *codebook.md*: which is the relative code book;
2- *tidyDS.csv* which is the required tidy data set in csv format;
3- *run_analysis.R* which is the R code file for this project. 
 
---




The submitted data set is tidy.
The Github repo contains the required scripts.
GitHub containsthat modifies and updates the available codebooks with the data to indicate all the variables and summaries calculated, along with units, and any other relevant information. 
 
 
 3) a code book that describes the variables, the data, and any transformations or work that you performed to clean up the data called CodeBook.md. 
 
 You should also include a README.md in the repo with your scripts. This repo explains how all of the scripts work and how they are connected.
 

You should create one R script called run_analysis.R that does the following.

Merges the training and the test sets to create one data set.
Extracts only the measurements on the mean and standard deviation for each measurement.
Uses descriptive activity names to name the activities in the data set
Appropriately labels the data set with descriptive variable names.
From the data set in step 4, creates a second, independent tidy data set with the average of each variable for each activity and each subject.
Good luck!
