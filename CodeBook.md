Explains all the variables in the Script
-----------------------------------------
-----------------------------------------

XtestData, YtestData --- are the two data tables read from the two "test" data files "X_test.txt" and Y_test.txt"

XtrainData, YtrainData --- same as above for the "train" text files


XtestData2, YtestData2, XtrainData2, YtrainData2 --- data table version of the respective files

XtestDataLabel, XtrainDataLabel -- XtestData2 and XtrainData2 with the "label"s 

trainData, testData --- the two "test" and "train" data sets with the values of the 561 activities, their respective "subject"s, and a marking for the data set i.e., whether it is from the "test" data set or the "train" data set

reqData --- is the merged data table of the trainData and testData

features --- data table of the "features" file having names of the 561 activities

reqDataMean, reqDataStd --- variables with the "mean()" and "std()" in their activity names respectively

reqDataMeanSub, reqDataStdSub --- subset of the two data tables based on the names

finalData --- merged data table of the two data sets


The variables names were then assigned to the columns 
The 6 activities are then labelled using the for loop
The respective cloumns were recognized as factor

tidyfinalData2 --- final tidy data set written down after grouping by the dplyr package


