# MSDS600_Natural_Language_Processing_Applications_and_Steps_Project_Manasi
Creation of account on reddit and save credentials in private file is one of the best practice while dealing with third party sources.
Overall this process helps to identify pattern and trends in reddit actions and user intercations.

- Reddit subreddit returns object as generator which generates values on demand i.e one at a time. 
- Hence we can collect it in list and then transfer it into data frame.
- For later use we can store data frame data into SQLite3 database.
- Each reddit post will save as row in database table.
- We can load data from database by using SQL query.
- Histogram for score colums shows how scores are distributed.
- Scatter plot for score and number of comments relationship which helps to identify patterns of highly scored posts gets more comments.
