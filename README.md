# Getting_and_Cleaning_data_Project

Step 1 : All the similar data is merged using the rbind() function.

Step 2 : Mean and standard deviation measures are taken from the whole dataset and the names are taken from features.txt.

Step 3 : As activity data is addressed with values 1:6, we take the activity names and IDs from activity_labels.txt and they are substituted in the dataset.

Step 4 : On the whole dataset, those columns with vague column names are corrected.

Step 5 : Generate a new dataset with all the average measures for each subject and activity type . The output file is called averages_data.txt
