# Course_Project
Getting and Cleaning Data

The script takes two data sets - 1)Train and 2) Test and combines them into one data set.
Both Train and Test data sets consists of three separate files mentioning different activities and the related measurements.

"reqData" is the table we got after combining the two data sets


Based on the names, the columns containing "mean()" and "std()" are selected using the grep command

"finalData" is the data with the required columns from the merged data set


Renaming the columns are done by the names given in the "features" file

Using for loops, naming if the 6 activity factors are done

After grouping the data using "group_by" in the dplyr package, the tidy data set is created by the name "tidyfinalData2"



