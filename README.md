# 2023 Hottest Motorcycle

This repository contains code to scrape motorcycle information from Yahoo Motorcycles, perform data processing using Pandas, utilize the OpenAI GPT-3.5 API for generating responses, store the data in a MSSQL database, and visualize the data using Matplotlib to create radar charts. Additionally, a Flask web application is built to display the collected information.

## Code

The code is written in Python and utilizes the following libraries:

- Requests: Used for web scraping Yahoo Motorcycles.
- BeautifulSoup: Used for parsing HTML content.
- Pandas: Used for data manipulation and processing.
- OpenAI: Used for accessing the GPT-3.5 API.
- PyODBC: Used for connecting to the MSSQL database.
- Matplotlib: Used for creating radar charts.
- Flask: Used for building the web application.

## Data Scraping

The code scrapes motorcycle information from the Yahoo Motorcycles website. It collects details such as name, frame, ranking, and price. The scraped data is then stored in a Pandas DataFrame.

## GPT-3.5 API Integration

The OpenAI GPT-3.5 API is used to generate responses regarding the perceived value and appearance of the motorcycles. The code prompts the API with specific questions and receives responses.

## Data Processing

The collected data is processed to calculate the CP value (cost-performance ratio) based on price ranges. The appearance of each motorcycle is also evaluated and assigned a rating.

## MSSQL Database

The data is stored in a MSSQL database using the PyODBC library. A table named "Bikes" is created to store the motorcycle information.

## Data Visualization

Matplotlib is used to create radar charts for each motorcycle category. These charts visually represent the rankings of different attributes.

## Web Application

A Flask web application is built to display the collected motorcycle information. The information is presented in a user-friendly format, including images, details, rankings, prices, CP values, and appearance ratings.



