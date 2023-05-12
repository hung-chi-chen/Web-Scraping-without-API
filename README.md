# Web-Scraping-without-API

# README
This project is a web scraping application that extracts data from Trustpilot.com websites and saves it in a structured format. The purpose of this project is to automate the process of data collection from websites, which can be time-consuming and error-prone when done manually. A total of 4 features will be extracted and later train with sentiment analysis as my NLP project. For the demostration purpose, I will use "Square" for my example. The features extraction is shown below. 

  - Company Name
  - DatePublished
  - RatingValue
  - ReviewBody

# Installation
To use this web scraping application, you need to have Python installed on your computer. You can download the latest version of Python from the official Python website. You also need to install the following libraries:

  - Beautiful Soup
  - Requests
  - Pandas 
  - Numpy

# Usage
To use this web scraping application, you need to specify the company review page where you want to extract ther data from.  You can modify the code in the url to specify the website and data fields.


The application will extract the specified data fields from the website and save it in a structured format, such as a CSV file or a database.

# Limitations
This web scraping application has some limitations that you need to be aware of. First, it may not work with all websites, especially those that have complex web page structures or use anti-scraping techniques. Second, it may violate the terms of service of some websites, which could lead to legal issues. Finally, it may not be able to extract all the data that you need, depending on the website and the data fields that you want to extract.
