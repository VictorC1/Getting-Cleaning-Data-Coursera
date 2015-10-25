Introduction

Read.tables -> Find Variables. #Read from Targeted Files in instructions 
Variables : Activity / Subject / Features /

#Read tables from target files into those features 
Files (Y_Test/Y_Train/subject_train/subject_test/X_test/X_train)
dataactivitytest <- read.table(file.path(path_rf, "test", "Y_test.txt"), header = FALSE)

#Find properties of the variables
> str()

#Merge tests sets into  one data set with wich variable
> rbind()
Set names to variables
>names() <-c()
#Merge collums to form data frame of all the data
cbind()

#Subset features by it's mean and standard deviation
subset()

#Read activity features from "activity_labels.txt"
read.table()
#add Activity into main data frame with descriptive name

#Set Labels on data frame with descriptive variable names
names(data <- gsub()

#Create a tidy data with mean from each variable of each activity and with subject

##This is the codebook
