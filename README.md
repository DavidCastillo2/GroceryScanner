# GroceryScanner
This is a starting point for a large project. At the time of development, this application could fully scrape Whole Foods. Any tweak to the webpage leads to the scraper needing the labels updated for the new site manually.

The scraped data is inserted directly into a database. There is a small Flask website for searching for items that are stored in the database. The website and web scraping are two separate programs that are run together inside of a docker container.
