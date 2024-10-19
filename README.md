# Web Scraping with Selenium
A project showcasing my skills web scraping data and getting into a useable format for analysis.
***

In this project:

* I captured the hyperlinks from the books on the first page of the site and stored them in a list.
* I then iterated over that list of urls gathering the title, price, and availability from the product pages
* I collected the attributes from the HTML content and stored them in their own respective lists.
* I created a data frame to contain all the data with correct headers.
* I removed text data from the 'Availability' column leaving only the number of books available in each row.
* I changed data types to numeric and did further converstion to type uint8 to save memory where possible.
* I plotted the distribution of the 20 book prices with Seaborn to show that the data is now in useable form.
* Delays were incorporated between requests as to not overload the server.
