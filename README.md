# scraping-oscar-winning-movies-imdb
### Scraping Oscar Winning Movies from IMDB using Python and Beautiful Soup
[Web Scraping](https://www.zyte.com/learn/what-is-web-scraping/) is the process of extracting data from web in a automated way. Here we scrape IMDb for getting movies data.


[IMDb](https://imdb.com/) is the world's most popular and authoritative source for movie, TV, and celebrity information. Watch trailers, get showtimes, and buy tickets for upcoming films. Rate and review shows you've seen and track what you want to watch using your Watchlist. IMDb takes you behind the scenes with exclusive IMDb Originals, celebrity interviews, and more.


The page https://www.imdb.com/search/title/?groups=oscar_winner&sort=year,asc provide list of [Oscar](https://en.wikipedia.org/wiki/Academy_Awards) winner movies in the ascending order of their release year and we are going to scrape some information for each movie like Movie Name, Runtime, Genre, Rating, Release year, Actors, Director and Poster. We'll use the Python libraries [requests](https://www.w3schools.com/python/module_requests.asp) and [beautifulsoup4](https://www.crummy.com/software/BeautifulSoup/bs4/doc/) to scrape data from this page.


Here are the steps which we are going to follow:

* Download the webpage using requests
* Parse the HTML source code using BeautifulSoup
* Extract Movie Name, Runtime, Genre, Rating, Release year, Actors, Directors and Poster from the page
* Store the extracted information into Python lists and dictionary
* Save the extracted information into a [CSV file](https://en.wikipedia.org/wiki/Comma-separated_values)

By the end of the project we'll create a CSV file in the following format:
![result csv](https://imgur.com/z7eR8ub)
