# What is Web scraping?
Web scraping is an automated method used to extract large amounts of data from websites. The data on the websites are unstructured. Web scraping helps collect these unstructured data and store it in a structured form. There are different ways to scrape websites such as online Services, APIs or writing your own code. In this article, we’ll see how to implement web scraping with python. 

# How Do You Scrape Data From A Website?
When you run the code for web scraping, a request is sent to the URL that you have mentioned. As a response to the request, the server sends the data and allows you to read the HTML or XML page. The code then, parses the HTML or XML page, finds the data and extracts it. 

Libraries used for Web Scraping 
As we know, Python has various applications and there are different libraries for different purposes.So, here I will be using the following libraries:
Requests library: The requests module allows you to send HTTP requests using Python.The HTTP request returns a Response Object with all the response data (content, encoding, status, etc). You can check the documentation [here](https://docs.python-requests.org/en/master/)

BeautifulSoup: Beautiful Soup is a Python package for parsing HTML and XML documents. It creates parse trees that is helpful to extract the data easily.[Documentation of BeautifulSoup](https://www.crummy.com/software/BeautifulSoup/bs4/doc/)

Pandas: Pandas is a library used for data manipulation and analysis. It is used to extract the data and store it in the desired format.

Here, I have scraped Flipkart website to extract the information of books. The URL for this page is :

https://www.flipkart.com/search?q=book&otracker=search&otracker1=search&marketplace=FLIPKART&as-show=off&as=off&p%5B%5D=facets.language%255B%255D%3DEnglish%27
![](https://github.com/Pragati019/Web-scraping-and-data-visualization/blob/main/Images/image1.png)


After extracting the data, you might want to store it in a format. This format varies depending on your requirement. For this example, I will store the extracted data in a CSV (Comma Separated Value) format.
So, The extracted information is then stored in CSV file.

Output:

![]()



