Web Scraping Homework - Mission to Mars

This repository includes files used to create a web application that scrapes websites for information about Mars Exploration displays the findings and images on a single site. Also incldued are screenshots of the site created.

To accomplish creating this, the following steps were taken:

Jupyter Notebook was created to design the scraping/ data collection:

For the latests in Mars News Headline: https://redplanetscience.com/

For an image of Mars crust: https://spaceimages-mars.com/

For facts about Mars: https://galaxyfacts-mars.com/

For images of Mars four hemispheres: https://marshemispheres.com/

Converted Jupyter notebook onto scrape_mars.py to execute the code for scraping the webites above and organize into a dictonary

Created an app.py importing Flask and pymongo to store the dictonary into Mongo and create a root route to query the database and route the scraped items to an HTML site for display.# web_scraping_challenge
 
