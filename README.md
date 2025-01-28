# Python-Profiling-Project

Project Description:
This project places you in an engagement with an airline client preparing and cleaning passenger satisfaction survey data to identify critical factors for improving service. The focus is on applying the process of preparing data for analysis by removing or modifying data that is missing, inaccurate, duplicated, or improperly formatted using Python.

Objectives:
Analyze business data using methods to determine the nature of the data for cleansing purposes.
Practice how to clean data to address missing, bad, or inaccurate data.
Practice data accessing to implement dataset importing and exporting.

Airline industries are devastated by the COVID-19 pandemic. Air travel is surging as people rush back for vacations, and the airline’s goal is to attract passengers to their business. Identifying the critical factors that lead to customer satisfaction can tell airlines what they can do to improve their service. Before analyzing data to answer the business questions, the data needs to be prepared and cleaned. Your domestic airline client needs help preparing and cleaning a dataset collected based on a passengers’ satisfaction survey. The collected dataset can be used to tell what factors are highly correlated to a satisfied (or dissatisfied) passenger. 

Conducting Data Access and Profiling:

To begin, read the survey dataset into a pandas DataFrame.
Then, create a subset of the DataFrame to include all passenger satisfaction data about only the Business Class. Name the created DataFrame subset “df_Business”.
Collect information about the “df_Business” dataset and its validity. Report the following:
The number of observations (or rows) and the number of variables (or columns) in the dataset.
The name and data type of each data column.
The unique values of each column.
The number of missing values of each column.
Summary statistics for each data column.
Frequency distribution (list the number of times each unique value appears) for each data column.
The number of fully duplicated data rows.
Based on the information that you collected, provide a list of the issues that the data contains as an annotation.
Supporting Materials

Conduct Data Cleansing:


Drop the Class column from the created Business Class passenger satisfaction survey (“df_Business”).
Rename “df_Business” columns by making all the columns’ names in lowercase, and if the column name has whitespace, replace it with an underscore. (For example: “Customer Type” will be renamed to “customer_type”).
Modify improperly formatted data and handle bad data.
Handle the missing values (You should have zero missing values in your cleaned dataset).
Remove the fully duplicated observations.
Fix the columns datatypes.
