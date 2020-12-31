# Kaggle Lending Club 
This project is based on the original Kaggle competition which occured in 2017 (https://www.kaggle.com/wendykan/lending-club-loan-data). Here, I attempt to classify Lenders into risky or safe borrowers and in so doing, predict whether they will default or pay their bills.

This project is broken into three sub projects:

## LC Data Prep
This sub-project contains the work I completed to download, extract, and munge the data. At the time of the analysis, I did not have enough RAM to analyze the eintre data set. Thus, I took a 20% sample of the data. The steps to performing the sample are in this folder.

**Important note**
Due to size limitations associated with my repository, I do not have the space capacity to upload the original, kaggle lending club data (1.7 Gb). This precludes being able to run rmd file "LC_data_cleaning.Rmd", making this portion of the project un-reproducible. 

The outcome of the code is the rds file "cleaneddata.rds", which is available to you.

## LC Data Analysis
This sub-project contains the code and files needed to perform the classification analysis.

