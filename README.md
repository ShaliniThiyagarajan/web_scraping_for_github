# web_scraping_for_github
## step by step Procedure:
-Downloading web pages using the requests library
-Inspecting the HTML source code of a web page
-Parsing parts of a website using Beautiful Soup
-Writing parsed information into CSV files
-Using a REST API to retrieve data as JSON
-Combining data from multiple sources
- Using links on a page to crawl a website

### summary
-with the help of the web scrapping , we easily collect any type data from any type of the website
-web scraping make the data scientist data collection job easy
-Here , collecting lakhs of data from different page. some pages will not load properly. At that point exeception will split out.
-Then we need to run the 'scrap_repo(topic_url)' line again for many times.
- Here we are created folder structure as
-
      -topic 'list of topics from different store its name, description, url'
      -topic_html ' list of Html pages for topic to be fetched'
      -data 'list of repository, will have different folder for each topic'
      -data_html' list of folder of different topic repository html page'
