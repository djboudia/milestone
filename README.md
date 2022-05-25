We are University of Michigan Master of Applied Data Science students interested in understanding correlations between college sports and crime incidents for University of Michigan’s and Michigan State University’s Football and Basketball teams.

This repo contains ten seasons of college football and basketball game data and Michigan criminal data from NIBRS (National Incident-Based Reporting System), 2009 to 2019. 


Our repo is structured with the following:

01_nibrs_rawdata/
-	 NIBRS data downloaded from https://crime-data-explorer.fr.cloud.gov/pages/downloads,  representing Michigan incidents/crimes. Each year’s data is stored as ‘MI-year’ (e.g. MI-2009).
-	 Contains guides and illustrations from NIBRS relevant interest to our analysis.

02_sports_rawdata/ 
  -	 Contains college football and college basketball data for University of Michigan and Michigan State University

03_notebooks/ 
-  Contains our Jupyter Notebooks used to compile data sources, merge data sets, and explore data:
  -	 01_nibrs_data - the notebook that combines nibrs data across the 10 year span
  -	 02_baskeball_data - web-scraping of college basketball data and extraction of gametimes using selenium 
  -	 03_eda_baseline - a notebook to evaluate the michigan crime data statewide with an attempt to get an understanding of criminal offenses that occur at the university locations. 
  -  04_join- data cleaning, manipulation and combining of the sports and crime data
  -	 05_sports_incidents_eda - our exploration of the data and creation of variables of interest that help us understand the relationships between aspects of the two universities and crime.

04_finaldata/
  -	 Contains full data used to combine and/or conduct our EDA

05_report/
  -	 .pptx and .pdf copies of final report


Please reach out if you have any questions about the data, inquiries about the analysis, or are curious to know more. Thanks!
