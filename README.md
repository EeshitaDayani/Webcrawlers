# Webscraper Projects

# Project Aim
The aim of the project was to create a program that tracks changes in the price and rating of objects on two popular websites.

The webscrapers built were required for:
  * eBayPriceTracker
  * GoodreadsRatingTracker

## Webscraper 1: eBayPriceTracker

Python script to track product prices on eBay using Beautiful Soup and Requests libraries. A request is made to the URL of the eBay product, and the HTML file is loaded. After the name and price of the product is extracted, the product price is compared to our maximum price (price we're willing to pay) in a time-updated while loop. When price our the product falls below our maximum price, a print statement is passed stating that the product is now at a suitable price. Additionally, we can also see a list of recommended items and their URLs.   

### Webscraper 2: GoodreadsRatingTracker 

Python script to track change in ratings of a book on Goodreads and Requests libraries. A request is made to the URL of the book, and the HTML file of the webpage is loaded. The name and current rating of the book is extracted. The current rating is then compared to a user-decided threshold value in a time-updated while loop. When the rating of the book rises above the minimum value, a print statement is passed alerting the user that the rating has increased past the threshold value. There is also a list of recommended books available to the user at the end of the program.


### Webscraper 3: NBA Tracker

TODO