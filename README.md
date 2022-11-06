
This notebook identifies the most common words in five large datasets covering the following themes: data engineering, data analytics, data science, software engineering and business analytics, as well as the most common words for the  five joined datasets as a whole. Datasets come in the form of csv documents, built from the webscraping of different webpages: GitHub, Documentation, Glassdoor and specific content sites (techical blogs and other similar sources). Some preprocess has already been put into the datasets, consisting mainly in the gathering and organizing of the obtained texts into one single csv file per category. The total amount of words in the five datasets is $3.204.121$<br>

We use a variety of libraries and packages including NLTK, collections, wordcloud, pandas, matplotlib and openpyxl. This report shows the steps that were followed, starting with the uploading of the datasets up until the writing of the excel files with the most common words per category. It includes the following sections:

0. Introduction<br>
1. Data Preprocess <br>
     1.1 Data Engineering Dataset<br>
     1.2 Software Engineering Dataset<br>
     1.3 Data Science Dataset<br>
     1.4 Data Analytics Dataset<br>
     1.5 Business Analytics Dataset<br>
2. Get Most Common Words<br>
3. Appendices<br>
     3.1 Dataframes of Clean Datasets<br>
     3.2 Write the Excel Files<br>
     3.2 Generate the Wordclouds
