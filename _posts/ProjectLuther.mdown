---
layout: post
title: Week 3 - October 3rd to October 7th - Project Luther
---

Project Luther took place during Week 2 & Week 3 of the Metis Data Science Bootcamp. For this project, we are using data that we scraped from the web (Using BeautifulSoup4) and then building regression models to find out some insights in the data. For this project, I used a data set from IMBD that contained 24 features. I also scraped BoxOfficeMojo's movie list from 1980 - 2005 finding 9 features including movie title (that is a given), distributor, release year, runtime,  domestic total gross, worldwide gross, foreign total gross, and opening weekend gross. 

With the existing data set that has 26 features and the 9 features, I was able to create a dataset that gave me some valuable insights into movies. One of the most difficult parts about the project was making sure the data was clean, the tables could be joined (so the titles had to match) in order to do any analysis. 

I wanted to do analysis to look into two questions. The first is what features will best predict how profitable a movie will be. The second is how do we best predict net promoter score (NPS). The second question could be answered because of the data set from IMDB. 

I will post more insights in an updated blog, but here are a few key learnings. 

*Scraping is a lot of trial and error, I scraped all of the HTML of BoxOfficeMojo and then scrape the pages from a folder I saved locally
*Cleaning the data and making sure your table joins work takes time
*Insights are not as easy to find as I would have liked