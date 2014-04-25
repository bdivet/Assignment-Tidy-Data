Assignment-Tidy-Data
====================
I used the read.table function to load the different files needed, which are kept under a folder /data in the working directory. I set as.is=TRUE to have integers and numbers instead of factors.
I used cbind to join subject_train, Y_train and X_train, then did the same for subject_test, Y_test and X_test then used rbind to merge the train and test data sets.
After loading features.txt, I used

