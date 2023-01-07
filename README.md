# **amazon-web-scraping**

1.Web Scraping is a technique to extract a large amount of data from several websites. The term "scraping" refers to obtaining the information from another source (webpages) and saving it into a local file.

2.Web Scrapping extracts the data from websites in the unstructured format. It helps to collect these unstructured data and convert it in a structured form.

### **How does Web Scrapping work?**
**Step -1: Find the URL that you want to scrape**

First, you should understand the requirement of data according to your project. A webpage or website contains a large amount of information. That's why scrap only relevant information. In simple words, the developer should be familiar with the data requirement.

**Step - 2: Inspecting the Page**

The data is extracted in raw HTML format, which must be carefully parsed and reduce the noise from the raw data. In some cases, data can be simple as name and address or as complex as high dimensional weather and stock market data.

**Step - 3: Write the code**

Write a code to extract the information, provide relevant information, and run the code.

**Step - 4: Store the data in the file**

Store that information in required csv, xml, JSON file format.

**-------------------------------------------------------------------------------------------------------------------------------------------------------------------**

**How to perform web scraping using the requests library and beautifulsoup library in Python.**

**Installation**
Install required packages.The basic command anywhere would be to open a command terminal and run,
> pip install requests
> pip install  bs4

**Requests Module**
Requests library is used for making HTTP requests to a specific URL and returns the response. Python requests provide inbuilt functionalities for managing both the request and response.

**BeautifulSoup Library**
BeautifulSoup is used extract information from the HTML and XML files. It provides a parse tree and the functions to navigate, search or modify this parse tree.
