# Nashville Housing Market Dataset Cleaned in PostgreSQL
#### This project idea was to showcase my ability to clean and manipulate data for better usage. I really enjoy SQL and doing interesting things with it. I did not actually do anything further with this cleaned data, but certainly could analyze to answer questions one may have.  An interactive dashboard may be a great addtion to this project to filter the data based on certain questions.  


##### In the dataset were roughly 85,000 rows of information on Nashville Housing.  I have included a screenshot of the data prior to cleaning. Things like date formats were not standardized, property addresses included the city and state, there were several null property addresses that needed to be populated as these were different from the owner address. There were several duplicates in the data as well, of which I was able to clean out using a Common Expression Table represented as a subquery in Postgres. 

![ScreenShot](https://github.com/ignizioj/NashvilleHousingDataCleaning-PostgreSQL/blob/main/UncleanedHousing.png) 

##### Below is a screenshot of the cleaned data.  A lot more could be done with this data to prep for analysis, but for the purposes of this project, I only did a few different things to make this data more usable.


![ScreenShot](https://github.com/ignizioj/NashvilleHousingDataCleaning-PostgreSQL/blob/main/CleanedHousing.png)

##### In addtion, I have included the PostgreSQL script in this repo for reference or information. Feel free to browse any files found in the repository.  I was the only contributer in this project.  Thanks!








