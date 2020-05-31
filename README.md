# Mission to Mars

![mission_to_mars](Images/mission_to_mars.jpg)

 built a web application that scrapes various websites for data related to the Mission to Mars and displays the information in a single HTML page. 
 The following outlines what you need to do.

## Scraping

Completed initial scraping using Jupyter Notebook, BeautifulSoup, Pandas, and Requests/Splinter.

* Created a Jupyter Notebook file called `mission_to_mars.ipynb` and used this to complete all of your scraping 
and analysis tasks. The following outlines what you need to scrape.

### NASA Mars News

* Scraped the [NASA Mars News Site](https://mars.nasa.gov/news/) and collected the latest News Title and Paragraph Text. 

### JPL Mars Space Images - Featured Image

* Visited the url for JPL Featured Space Image (https://www.jpl.nasa.gov/spaceimages/?search=&category=Mars).

* Used splinter to navigate the site 

### Mars Weather

* Visited the Mars Weather twitter account(https://twitter.com/marswxreport?lang=en) and scraped the latest Mars weather tweet from the page. 

### Mars Facts

* Visited the Mars Facts webpage (http://space-facts.com/mars/) and used Pandas to scrape the table containing facts about the planet including Diameter, Mass, etc.

* Used Pandas to convert the data to a HTML table string.

### Mars Hemispheres

* Visited the USGS Astrogeology site (https://astrogeology.usgs.gov/search/results?q=hemisphere+enhanced&k1=target&v1=Mars) 
to obtain high resolution images for each of Mar's hemispheres.

- - -

## Step 2 - MongoDB and Flask Application

Used MongoDB with Flask templating to create a new HTML page that displays all of the information that was scraped from the URLs above.
- - -


