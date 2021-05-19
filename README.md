# Mission to Mars

## Overview of project<br>

A web scraping project to retrieve Mars related information from 4 different websites.<br>

For this process BeautifulSoup and Splinter from Python was used to extract the preferred data and display it on a Flask web application.  Extracted data includes the lastest news about Mars, the featured image, facts about Mars and the images with titles of the Mars hemisphere. <br>

The code created in the [scraping.py](https://github.com/taranahassan/Mission-to-Mars/blob/main/scraping.py) has been automated for the lastest news and featured image which allows the information to be updated with new information everytime the code is run.<br>

The mars facts table was extracted and converted into a dataframe table which will also can be updated everytime the code is run. <br>
The last part of the data, images and titles of Mars hemispheres were scraped and stored in MongoDb, which then transfered onto Flask.


#### Data source:

https://mars.nasa.gov/news/ <br>
https://data-class-jpl-space.s3.amazonaws.com/JPL_Space/ <br>
http://space-facts.com/mars/ <br>
https://astrogeology.usgs.gov/search/results?q=hemisphere+enhanced&k1=target&v1=Mars <br>


#### Software used:

- Python 3.7.9
- Splinter 0.14.0
- Beautifulsoup 4
- Flask 1.1.2
- Bootstrap 3
- Jupyter Notebook and VS code for code editng



## Summary

![html.png](https://github.com/taranahassan/Mission-to-Mars/blob/main/image/html.png?raw=true) <br>

Above image has been formatted for better visual using Bootstrap 3.
