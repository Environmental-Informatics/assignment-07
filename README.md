# Environmental Informatics

## Assignment 07 - Graphical Analysis with Python

### Lab Objectives

On completion of this lab, students will be able to:
1. 

### Reading Assignment

Data Analysis with Open Source Tools Chapters 2 and 3.

### The Lab Assignment

Start by downloading the data for this assignment as follows:

- Go to the [USGS earthquake hazards web site](http://earthquake.usgs.gov/earthquakes/feed/) and download data on recent activity in the "Spreadsheet Format" to get data in a CSV file. 

- Select "All Earthquakes" for the past "30 days". 

- Save It will be a CSV file, and its contents are described at the site (5 pts, submitted with your final program). 

- You will need to document this process (including date and time of download) for your metadata file.

Next, write a Python script to complete the following tasks:

1. Open and read the contents of the file into Python.

   - You will quickly find that the numpyfunction genfromtxt() will not work with this data file.  Why not?  (2 pts, answer in metadata file)

   - The best option for reading this file will be to make use of the read_csv() method within the pandas module (5 pts, using read_csv to read file and populate a dataframe).

   - For a tutorial introducing features of pandas and its dataframe data type work through the tutorial material as [10 minutes to pandas](see http://pandas.pydata.org/pandas-docs/stable/10min.html).

   - Much of what you learned for working with numpy arrays last week, will apply to dataframes as well, but there is a difference in how you index and slice them (an improvement over numpy structured arrays).

   - Don't worry about understanding date and time in pandas (or Python for that matter), we will focus on the date and time concepts in an upcoming later in the semester.

   - The pandas dataframe is built to handle heterogeneous data (data that is not all the same), as opposed to numpy, which is designed for homogeneous data (data that is all the same).  It brings back more of the flexibility of Python lists, but is built relying on the more powerful numpyarray data type.

3. Using matplotlib conduct the following graphical analysis of the data:
   - Generate a histogram of earthquake magnitude, using a bin width of 1 and a range of 0 to 10 (4 pts)
   - Generate a KDE plot for the same data, be sure to indicate selections for the kernel and kernel width in the metadatafile, comment in the metadatafile about similarities and differences in what you see between the histogram and KDE plots (6 pts)
   - Plot latitude versus longitude for all earthquakes, and comment on the distribution of those points in the metadatafile (4 pts)
   - Generate a normalized cumulative distribution plot of earthquake depths, and comment on what the plots shows you about their distribution (4 pts)
   - Generate a scatter plot of earthquake magnitude (x-axis) with depth (y-axis), comment on what this shows you in your metadata file. (4 pts)
   - Generate a quantile or Q-Q plot of the earthquake magnitudes.  What statistical distribution does your Q-Q plot assume, and does your data comply with that distribution? (4 pts)

4. Be sure that the script has a complete header comment block, appropriate in-line comments, and runs without intervention (5 pts)

5. Generate a metadata file, this time use Word or similar word processing program (7 pts).
   - Describe the source and format of the input data (not more than half a page),
   - Describe the types of analysis conducted by your script (not more than half a page),
   - Import the graphical analysis figures your developed in the previous section, and

6. Discuss the results of your analysis guided by the questions above.  Answers should not be more than 3-4 sentences.

1. Start by downloading the data for this assignment as follows:
Go to the [USGS earthquake hazards web site](http://earthquake.usgs.gov/earthquakes/feed/) and download data on recent activity in the "Spreadsheet Format" to get data in a CSV file. 

2. Select "All Earthquakes" for the past "30 days". 

3. Save It will be a CSV file, and its contents are described at the site (5 pts, submitted with your final program). 

   - You will need this information for your metadata file.

Write a Python script to completethe following tasks:

1. Open and read the contents of the file into Python.
   - You will quickly find that the numpyfunction genfromtxt() will not work with this data file.  Why not?  (2 pts, answer in metadata file)

2. The best option for reading this file will be to make use of the read_csv method within the pandas module (5 pts, using read_csv to read file and populate a dataframe).
   - For a tutorial introducing features of pandas and its dataframedata type see http://pandas.pydata.org/pandas-docs/stable/10min.html.
   - Much of what you learned for working with numpy arrays last week, will apply to dataframes as well, but there is a difference in how you index and slice them (an improvement over numpy structured arrays).
   - Don't worry about understanding date and time in pandas (or Python for that matter), we will focus on the date and time concepts later in the semester.
   - The pandas dataframe is built to handle heterogeneous data (data that is not all the same), as opposed to numpy, which is designed for homogeneous data (data that is all the same).  It brings back more of the flexibility of Python lists, but is built relying on the more powerful numpyarray data type.

3. Using matplotlib conduct the following graphical analysis of the data:
   - Generate a histogram of earthquake magnitude, using a bin width of 1 and a range of 0 to 10 (4 pts)
   - Generate a KDE plot for the same data, be sure to indicate selections for the kernel and kernel width in the metadatafile, comment in the metadatafile about similarities and differences in what you see between the histogram and KDE plots (6 pts)
   - Plot latitude versus longitude for all earthquakes, and comment on the distribution of those points in the metadatafile (4 pts)
   - Generate a normalized cumulative distribution plot of earthquake depths, and comment on what the plots shows you about their distribution (4 pts)
   - Generate a scatter plot of earthquake magnitude (x-axis) with depth (y-axis), comment on what this shows you in your metadata file. (4 pts)
   - Generate a quantile or Q-Q plot of the earthquake magnitudes.  What statistical distribution does your Q-Q plot assume, and does your data comply with that distribution? (4 pts)

4. Be sure that the script has a complete header comment block, appropriate in-line comments, and runs without intervention (5 pts)

5. Generate a metadata file, this time use Word or similar word processing program (7 pts).
   - Describe the source and format of the input data (not more than half a page),
   - Describe the types of analysis conducted by your script (not more than half a page),
   - Import the graphical analysis figures your developed in the previous section, and

6. Discuss the results of your analysis guided by the questions above.  Answers should not be more than 3-4 sentences.

#### What to turn in...

7. Put your input file, processing script and metadata file into a separate directory (directory should be named: "<username>_Lab7", where <username> is your Purdue career ID).  Zip or tar the directory, and submit via Blackboard.



