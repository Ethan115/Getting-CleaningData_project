This repo includes the following files:

* run_analysis.R
* code_book.md
* README.md

### run_anlysis.R
>Make sure the data folder "UCI HAR Dataset" is in the working directory with this R script.

>This R script reads and merges train and test data sets and includes activity and subject id information. It also selects only the mean and standard deviation of each measurement. It relabels the column names and activity factors to make them descriptive.Finally it outputs a second and independent data set with the average of each variable for each activity and each subject.

In detail, it achieves the output data set with the following steps:

* Read features.txt for later features selection and column names.
* Read the test data, select the features and combine with activity and subject id.
* Read the train data, select the features and combine with activity and subject id.
* Merge train and test data sets.
* Change the activity labels to be descriptive.
* Melt and Cast the data.
* Output the data set "complete.cast" and write into text file "merged_data.txt”.


### code_book.md
>Code book describes each variables in the data set.


### README.md
>This current markdown file explains files in the repo.