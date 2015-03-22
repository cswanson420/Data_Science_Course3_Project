This README explains the generation of a tidy dataset based upon
the data from http://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones.

The link for the data is:

https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip 

To use the R script in the repository: 

https://github.com/cswanson420/Data_Science_Course3_Project

unzip the data file in the same directory as the R script run_analysis.R with:

unzip getdata-projectfiles-UCI HAR Dataset.zip

(This unzip command assumes a UNIX based Operating System. Otherwise use the relevant tool for your
Operating System)

The data is located in subdirectories ./test and ./train.
The R script must have these subdirectories relative to the working directory
of the script.

The tidy_data.txt output file from run_analysis.R has 181 observations with 4 variables.

The variables are:
1) subject. An integer indicating a discrete subject.
2) activity. A factor of ["WALKING", "WALKING_UPSTAIRS", "WALKING_DOWNSTAIRS","SITTING", "STANDING"]
3) mean. The mean of means for all observations from the original data in the zip file.
3) std. The standard deviation of standard deviations for all observations from the original data in the zip file.
