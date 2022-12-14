# Module_8 - Crowdfunding: ETL 

## Overview of the analysis:

### Deliverable 1: Extract Data

Using the python dictionary method I extracted the data from the backer_info.csv file into a DataFrame. 

![backers](images/backers.png "Backers")

### Deliverable 2: Transform and Clean Data

Using the python to split up columns and re-organize them to produced the cleaned backers DataFrame below. The column name was also dropped. 

![backers_cleaned](images/backers_cleaned.png "Backers Cleaned")

### Deliverable 3: Create an ERD and a Table Schema and Load the Data

Updating the ERD map to include the new backers table. Through reviewing the backer tables properties, I was able to succesfully import the csv into the table. 

![load_check](images/load_check.png "SQL Load Check")


### Deliverable 4:

There are 8,175 items in the backer table. 

      SELECT COUNT(cf_id)
      FROM backers;


   ![Mentorship_by_title](images/Mentor_by_title.png "Mentorship Eligibility Titles")
   ![Mentorship_total](images/Mentor_total.png "Mentorship Eligibility Total")
