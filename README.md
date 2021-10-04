
# Introduction to Web Scaping 
It is a form of copying in which a speific data is from the web into a local database or spreadsheet and use for later retrieval or analysis.

# Problem Statement
GitHub contains millions of repositories. In this project we are going to use the GitHub topics page and from the topic page we are going to find the list of topic for each repositories and then going to downlaod it. 
      
# Steps Required to do Web Scraping 
1.Pick a website and identify the information that you want to scrape.
2.Outline your objective including the format of the output CSV file and summarize it in your Jupyter notebook
3.Use Requests librabry to downlaod the page .
4.Inspect the website's HTML source and identify the right URLs to download.
5.Use Beautiful Soup to parse and extract information.
6.Create functions to extract from the page into lists and dictionaries.
7.Create CSV file(s) with the extracted information.
8.Verify the information in the CSV files by reading them back using Pandas.

# Libraries used in this Project

 - Requests 
 - BeautifulSoup 
 - Pandas
 
If you want to know more about the Python librabires used for web scraping you can check the link below:
https://towardsdatascience.com/choose-the-best-python-web-scraping-library-for-your-application-91a68bc81c4f


# Project Outline

We'll get a list of topics by scraping https://github.com/topics. 
We'll get the topic title, topic page URL, and topic description for each topic.
From the topic page, we'll get the top 25 repositories for each topic.
For each repository We'll get the name, username, stars, and URL.
For each topic we'll create a CSV file in the following format:
      Repo Name,Username,Stars,Repo URL
      three.js,mrdoob,69700,https://github.com/mrdoob/three.js
      libgdx,libgdx,18300,https://github.com/libgdx/libgdx  


