## Files Overview

f1_final_df: CSV file with final version of data scraped from website.

f1_prezi: PDF file with presentation slides. *(I used a platform called Prezi and had some animation in my presentation which can be seen in my presentation video. 
That is why you will see slides repeated in the PDF version)

F1_wbk: Tableau Workbook with a simple dashboard created out my data exploration.

F1WebScrapingProject: (IPYNB file) Python notebook with all code for web scraping, data cleaning and processing. 

fatal_history: CSV file data scraped for further analysis.

Images Folder: Images from the utilization of Snowflake data warehouse and visualizations through EDA with SQL.


I completed all the web scraping and data cleaning utilizing python and BeautifulSoup within the Jupyter environment and saved the final dataframe as a csv file in a S3 bucket.
Next I connected to the S3 bucket with a Snowflake data warehouse created a database and tables. I utilized SQL to create some visualizations within the Snowflake environment.
Finally I connected my data warehouse to Tableau and created a simple dashboard of my analysis and exploration to be abale to visualize my findings in more depth.

