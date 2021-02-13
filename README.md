## Files Overview

Web scraped F1 winners data for every GP and created a data warehouse in Snowflake and created EDA visualizations in Snowflake

f1_final_df: CSV file with final version of data scraped from website.

f1_prezi: PDF file with presentation slides. 
*(I used a platform called Prezi and had some animation in my presentation which can be seen in my presentation video. 
That is why you will see slides repeated in the PDF version)

F1_wbk: Tableau Workbook with a simple dashboard created out my data exploration.

F1WebScrapingProject: (IPYNB file) Python notebook with all code for web scraping, data cleaning and processing. 

fatal_history: CSV file data scraped for further analysis.

Images Folder: Images from the utilization of Snowflake data warehouse and visualizations through EDA with SQL.


I completed all the web scraping and data cleaning utilizing python and BeautifulSoup within the Jupyter environment and saved the final dataframe as a csv file in a S3 bucket.
Next I connected to the S3 bucket with a Snowflake data warehouse created a database and tables. I utilized SQL to create some visualizations within the Snowflake environment.
Finally I connected my data warehouse to Tableau and created a simple dashboard of my analysis and exploration to be abale to visualize my findings in more depth.

![Snowflake Data Warehouse](https://github.com/Manny-Brar/F1-WebScraping-SnowflakeDB/blob/main/Snowflake1.jpg)

![Web Scraping Processed Data Frame](https://github.com/Manny-Brar/F1-WebScraping-SnowflakeDB/blob/main/bandicam%202020-10-20%2012-36-06-949.jpg)

![Snowflake Visualization - Most GP Wins](https://github.com/Manny-Brar/F1-WebScraping-SnowflakeDB/blob/main/Most%20Grand%20Prix%20Wins%20by%20Team%20(All-Time)%20.png)

![Tableau Dashboard](https://github.com/Manny-Brar/F1-WebScraping-SnowflakeDB/blob/main/F1_Dash.png)
