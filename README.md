# Data Collection Challenge: Module 11

## Objective

The goal for this challenge was to scrape web data from a Mars news and weather site and then generate deliverables that parse and store the recent news stories and perform data analysis of Mars' weather cycles. This was performed on Python and Jupyter notebook using BeautifulSoup and Splinter. Dataframes and charts were generated with Pandas and Matplotlib, respectively. 

### Mars News Web Scraping
The code uses a function with a for loop to parse through the website and query a list of the title and preview of every Mars news article on the page.

### Mars Weather Data Analysis

After scraping the table data from the website, this code also converts the information into a dataframe, and converts the data types to enable statistical analysis. From here, the dataframe is used to generate charts of the average minimum daily temperature on Mars, a monthly breakdown of the lowest and highest atmospheric pressure, and finally a plot of the daily minimum temperature to visually estimate the number of terrestrial days exist in a Martian year. Afterwards, the code exports the dataframe to a csv file.

## Attributions

All information sourced and generated in this code is from the course material:<br/>
- The Mars News website is operated by edX Boot Camps LLC for educational purposes only. The news article titles, summaries, dates, and images were scraped from NASA's Mars News website in November 2022. Images are used according to the JPL Image Use PolicyLinks to an external site., courtesy NASA/JPL-Caltech.
    - 'https://static.bc-edx.com/data/web/mars_news/index.html'
    - 'https://static.bc-edx.com/data/web/mars_facts/temperature.html'