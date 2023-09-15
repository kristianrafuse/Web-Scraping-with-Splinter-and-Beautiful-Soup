Web Scraping with Splinter and Beautiful Soup
-------
In this example, I extract information via automated browsing with Splinter and HTML parsing with Beautiful Soup. Here, I scrape titles and preview text from Mars news articles, and analyze Mars weather data, which exists in a table on one of the sites. Essentially, this project is about collecting data, organizing and storing data, analyzing data, and then visually communicating my insights.

Mars Information
-------
Use automated browsing to visit the Mars news site.
Create a Beautiful Soup object and use it to extract text elements from the website.
Extract the titles and preview text of the news articles, store the scraping results in Python data structures in a Python dictionary, and give each dictionary two keys: title and preview.

Mars Weather
-------
Use automated browsing to visit the Mars Temperature Data Site.
Create a Beautiful Soup object and use it to scrape the data in the HTML table.
Assemble the scraped data into a Pandas DataFrame with the following columns created:

* id: the identification number of a single transmission from the Curiosity rover.
* terrestrial_date: the date on Earth.
* sol: the number of elapsed sols (Martian days) since Curiosity landed on Mars.
* ls: the solar longitude.
* month: the Martian month.
* min_temp: the minimum temperature, in Celsius, of a single Martian day (sol).
* pressure: The atmospheric pressure at Curiosity's location.

Analyze the dataset by using Pandas functions to answer the following questions:
* How many months exist on Mars?
* How many Martian (and not Earth) days worth of data exist in the scraped dataset?
* What are the coldest and the warmest months on Mars (at the location of Curiosity)?
* Find the average minimum daily temperature for all of the months.
* Plot the results as a bar chart.
* Which months have the lowest and the highest atmospheric pressure on Mars? 
* Find the average daily atmospheric pressure of all the months.
* Plot the results as a bar chart.
* About how many terrestrial (Earth) days exist in a Martian year?
* Visually estimate the result by plotting the daily minimum temperature.



