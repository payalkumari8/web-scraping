
# Introduction to Web Scaping 
It is a form of copying in which a speific data is from the web into a local database or spreadsheet and use for later retrieval or analysis.

# Problem Statement

GitHub contains millions of repositories. In this project we are going to use the GitHub topics page and from the topic page we are going to find the list of topic for each repositories and then going to downlaod it. 
      
# Project Outline

Get a list of topics by scraping https://github.com/topics. 
Get the topic title, topic page URL, and topic description for each topic.
From the topic page, get the top 25 repositories for each topic.
For each repository get the name, username, stars, and URL.
For each topic, create a CSV file in the following format:
      Repo Name,Username,Stars,Repo URL
      three.js,mrdoob,69700,https://github.com/mrdoob/three.js
      libgdx,libgdx,18300,https://github.com/libgdx/libgdx  

  


# Libraries used in this Project

 - Requests 
 - BeautifulSoup 
 - Pandas
 
If you want to know more about the Python librabires used for web scraping you can check the link below:
https://towardsdatascience.com/choose-the-best-python-web-scraping-library-for-your-application-91a68bc81c4f




