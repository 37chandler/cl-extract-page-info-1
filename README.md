# Extracting Craigslist Page Info Part 1

In the first phase of our Craigslist (CL) car scraper, we extracted links  from the search results pages. In this assignment 
we extract some of the more basic page elements from the listing pages. 

I've extracted 168 HTML pages from various CL sites. Those files are stored in the zip `listing_html_pages.zip`. I'd recommend just extracting that file manually to a folder location on your machine. Once you've done that, write code to extract the key pieces of information from the listing pages. 

Here are the fields I'd like you to extract from the listing page for this first part: 

* Post ID (this is in the file name and is part of the URL)
* Title Text (from the `postingtitletext` div)
* Posting Body Text (from the `postingbody` div)
* Price
* Year
* "Crumb Area", the location within the CL breadcrumb list
* Mileage (called "odometer" when it's present in the left-hand list called "attrgroup")
* Posting Date

This is not easy, as these pages can be very messy. Good luck!

