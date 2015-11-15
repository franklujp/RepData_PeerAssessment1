# Reproducible Research: Peer Assessment 1


## Loading and preprocessing the data

   After Setting the working directory, running the code below will download and 
   unzip the file required this assignment.
  

```r
#DataUrl <- "https://d396qusza40orc.cloudfront.net/repdata%2Fdata%2Factivity.zip"
zipFile <- "./activity.zip" 
#download.file(DataUrl, destfile = zipFile, method = "wininet")
FDataFactivity <- unzip(zipFile)
ActivityMonintorData <- read.csv(FDataFactivity, header = T, sep = ",")
```

## What is mean total number of steps taken per day?



## What is the average daily activity pattern?



## Imputing missing values



## Are there differences in activity patterns between weekdays and weekends?
