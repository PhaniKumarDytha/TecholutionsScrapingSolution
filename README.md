# TecholutionsScrapingSolution
Solution for scraping the job openings posted in Techolutions site

Objective: Scrap the data from Techolution Careers website and store the data according to the date of posting(Most old first) as a DataFrame in CSV.

Approach Followed: Since the Site is rendered by javascript I've used selenium webdriver to take up the data from the site and I managed to scrape the data upon identifying the tags as mentioned in the Jupyter notebook Uploaded. 
Once the datascraping is done the next objective is to store the data into dataframe and then store it in a csv file having the Most old first. 

The parsing of the dates which are there in the format '1 day ago', '2 days ago', '1 month ago' is done using the python package dateparser and then sorted according to the dates obtained to show Most old first

Packages Used: 
pandas, selenium, dateparser