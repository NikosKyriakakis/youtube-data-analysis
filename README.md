# youtube-data-analysis
Data management and analytics using MongoDB for youtube videos. Inside the queries.mongodb file, one can find the MongoDB code which fetches the appropriate results for the following statements.

* Query 2.1: Display the title, views and number of likes and dislikes for the "Saturday Night Live" channel. Sort the results in descending order according to the number of views.

* Query 2.2: Find out the video id, the number of tags, and the number of views in descending order according to the number of views. 

* Query 2.3: Display all unique tags and the associated number of videos which use this tag in descending order according to the number of videos, for both USA and Great Britain

* Query 2.4: Calculate the average likes and dislikes for videos which have their comments disabled and for those which don't. Sort results according video count in descending order.

* Query 2.5: Display the number of videos which have been published during the last 3 months (5th of November 2017 - 5th of March 2018). For each record, show the date when the video was uploaded in a format like year-month-day and the associated video count, sorted from the oldest to newest.

**User guide:** create a new mongo database and 2 collections, namely GB and USA. Then load the data found in the next link https://drive.google.com/drive/folders/1uvU7z5ZzFnWICusrCPkgrnACtMg5buH5?usp=sharing
