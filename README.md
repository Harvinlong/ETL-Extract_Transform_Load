## ETL for Crowdfunding Data
This project involves performing an ETL process on a new dataset containing information about the backers who’ve pledged to live crowdfunding projects. Involves using Python, Pandas, and Jupyter notebooks to extract and transform the backers’ contact information from a CSV file and create a DataFrame that will be exported as a CSV file. Finally, data analysis on the database will be performed using SQL queries.

## Process
The purpose of this project is to perform an ETL process on a CSV file containing information about backers who pledged to live crowdfunding projects. 

The process involves iterating through the DataFrame to convert each row into a dictionary, extracting the required values using Python dictionary methods and regular expressions to create a new DataFrame.

Splitting the names in the "name" column into first and last names and adding to their respective columns in the DataFrame. 

Finally, the "name" column is dropped, and the resulting DataFrame is exported as CSV file. The data analysis is performed using SQL queries on the crowdfunding database.

![data-8-final-backers-DataFrame](https://user-images.githubusercontent.com/111480084/225502278-0caa9e9c-7b9f-422d-9375-a73d522fa40c.png)

Using the SQL queries to retrieve the number of backers counts in descending order for each campaign, confirming the results from the previous step, and creating a new table that contains the email addresses of the backers, first and last name of each backer, company name, description, the end date of the campaign, and the remaining amount of the campaign goal.

![data-8-email_backers_remaining_goal_amount](https://user-images.githubusercontent.com/111480084/225504475-e1c2b08f-3b99-4478-850a-f1924e3ec429.png)
