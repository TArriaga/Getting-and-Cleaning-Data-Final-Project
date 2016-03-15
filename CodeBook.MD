#Introduction
The script run_analysis.R performs the 5 steps described in the course project's definition (vide README.MD file).

###Brief Description of the Code

* Similar data (files having the same number of columns, refering to the same entity) is merged using the rbind() function. 
* Only columns with mean and standard deviation measures are taken from the whole dataset. 
* Those columns are given the correct names, taken from features.txt.
* Activity data is addressed with values 1:6, so activity names and IDs are taken from activity_labels.txt and substituted in the dataset.
* At last, new dataset containing all the average measures for each subject and activity type (30 subjects * 6 activities = 180 rows) is generated.
The output file is called averages_data.txt, and uploaded to this repository.

#### Variables in the Code
* :_train and :_test (: = x, y, subject) variables contain the data from the downloaded files.
* :_data (: = x, y, subject) variables merge the downloaded datasets for further analysis. Those variable will be all merged in a big dataset - all_data variable.
* features contains the correct names for the x_data dataset.
* averages_data variable contains the relevant averages which will be later stored in a .txt file. 
