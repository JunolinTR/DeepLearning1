# DeepLearning1
Byte Club

In this project, we are going to make use of several Python libraries that can automate the process of web scraping and extraction. First of all, we import all the necessary libraries for making HTTP requests, parsing HTML content, performing regular expression operations, or handling data output in CSV format.

Then, we have created a script that would send HTTP requests to the website of wikiHow for fetching random blog posts. On each page, we parse its HTML content for extracting the subheadings and paragraphs. After extraction, we cleaned the text using regular expressions so that there were no additional characters.

Then, the title, subheadings, and the respective paragraphs extracted from the data are written in a CSV. This was the general automated approach toward scraping and structuring data coming from thousands of wikiHow articles, hence giving us a robust dataset for further analysis or machine learning tasks.
