# ProjectMedTech
There are 2 elements to the codes. 
 1. The forums
 2. The clinical Trial Website

 - The Forums
 The crawlers to scrape the website are located in the ProjectMedTech\Web Scraping\forums\Scrappers sub-folder:
    - antidepressants_scrapper_collated.ipynb
    - cancerresearch_forum.ipynb
    - webmd_forums
    - reddit_scrapper.ipynb (located inside the Reddit Folder)

The CSVs for all these sites are located ProjectMedTech\Web Scraping\forums\csvs\Scrapped_Data

- Clinical Trial website
The code to scrape for clinical trials are located in the ProjectMedTech\Web Scraping\websites:
1) Make use of Selenium to pull out all the information. The code for the webscraping is named under 'Clincial_Trials_Webscrape_2.ipynb'
We have split the data into 3, due to the file size namely, 1st_Clinical_Trials_data.zip,2nd_Clinical_Trials_data.zip,3rd_Clinical_Trials_data.zip

2) Next, we clean our data and apply sentimental analysis and exploratory data analysis on the clinical trials to identify which topics are the most frequently researched among all the clinical trials. The code for the analysis is named under 'medtech_DataCleaning_v3.ipynb'

Documenatation for each notebook is located within each notebook

