# Cleaning_mapping_NY_SATdata_matplotlib_basemap

The overall goal here is concerned with determining demographic factors that correlate with SAT score.

The main data frame is the SAT Results data set. It is kind of the response or dependent data frame. The goal is to detect correlations or make predictions of SAT results using the demographic data sets like class size, school demographics, graduation results and so on.

Two different methods are used to import the data files.
Using an API to import the data as json-files. 
Reading in files from directory using glob and store theses in a dictionary.

The relationships between the different  data sets can easier be investigated by merging these into one data frame.
For this purpose different steps of data preprocessing must be taken.
For example a unique identifier (primary key) must be created, which allows to join the data sets.

Additional research question:

New York City has a significant immigrant population and is very diverse, so comparing demographic factors such as race, income, and gender with SAT scores is a good way to determine whether the SAT is a fair test. For example, if certain racial groups consistently perform better on the SAT, we would have some evidence that the SAT is unfair.
