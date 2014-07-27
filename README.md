Getting and Cleaning Data: Peer Assessment Project
=========================================

This repository contains the course project for the Coursera course "Getting and Cleaning data", part of the Data Science specialization.

About the Dataset(training and test)
------------------------------------

The features (561 of them) are unlabeled and can be found in the X_test.txt. 
The activity labels are in the Y_test.txt file.
The test subjects are in the subject_test.txt file.

Similarly for the training set, there are three files, X_train.txt, Y_train.txt, subject_train.txt respectively.


About the script and the tidy dataset
-------------------------------------
The R script called run_analysis.R will merge the test and training sets together.
Requirements for this script:

1. the UCI HAR Dataset must be extracted and..
2. the UCI HAR Dataset must be availble in a directory called "UCI HAR Dataset"

After merging testing and training, labels are added and only columns that have to do with mean and standard deviation are kept.

Lastly, the script will create a tidy data set containing the means of all the columns per test subject and per activity.
This tidy dataset will be written to a tab-delimited file called tidy_dataset.txt, which can also be found in this repository.

The Code Book
-------------------
The CodeBook.md file explains the transformations performed and the resulting data and variables.
