# ProKabaddi-season7-prediction
Heckathon to prediction the outcome of Pro Kabaddi League for Season 7 Oct 2019
We have used Python, Selenium Chrome Web Driver, Beautiful Soup to perform Web Scraping of data
There are multiple data generate from different part of the https://www.prokabaddi.com portal
1) All team information is extracted from https://www.prokabaddi.com/teams/<each team name> 
(example: https://www.prokabaddi.com/teams/bengal-warriors-profile-4 gives the information about begal warriors team data)
2) Another source of team information is extracted from https://www.prokabaddi.com/stats (using Team tab)
3) The player data is extracted from https://www.prokabaddi.com/stats (using Player tab)
4) Each match information is extracted from https://www.prokabaddi.com/schedule-fixtures-results 
(using drop down for month selection and season for season selection)
5) All extracted data is formatted as CSV files and stored in the local folder (working directory of python)
6) There are number of analysis performed on the generated data
7) We excluded Season1,2 and 3 as some of the team are started from Season 4 only. 
   So the data will become imbalance if we use the entire season for prediction
8) We set aside Season 7 data for later prediction to compare the trends
9) We tried various model for prediction (Linear, Logistic , KNN, K-means) , but none of them are accurate as the data is less and volatile
10) We finally attempted to predict using simple EDA methods. The trend is very clear and vivid using various graphs.
11) This proves that ML modeling is not required when simple EDA will do

Usage Information:
1) Download/Pull all iPython Notebooks
2) Execute the file as per the header information one by one.
3) Three iPython files will extract data from https://www.prokabaddi.com
4) Execute the last iPython notebook for analysis
5) Other option is to download/pull Zip file and unzip the same to extract all data into your working directory


