# web-scraping-challenge
This new assignment consists of two technical products. You will submit the following deliverables:

### Deliverable 1: Scrape titles and preview text from Mars news articles.

### Deliverable 2: Scrape and analyze Mars weather data, which exists in a table.

# Part 1: Scrape Titles and Preview Text from Mars News
1. Open the Jupyter Notebook in the starter code folder named part_1_mars_news.ipynb. You will work in this code as you follow the steps below to scrape the Mars News website.
2. Use automated browsing to visit the Mars news siteLinks to an external site.. Inspect the page to identify which elements to scrape.
Create a Beautiful Soup object and use it to extract text elements from the website.
3. Extract the titles and preview text of the news articles that you scraped. Store the scraping results in Python data structures as follows:
4. Store each title-and-preview pair in a Python dictionary and, give each dictionary two keys: title and preview. 
5. Store all the dictionaries in a Python list.
6. Print the list in your notebook.
7. Optionally, store the scraped data in a file (to ease sharing the data with others). To do so, export the scraped data to a JSON file. (Note: there will be no extra points for completing this.)

# Part 2: Scrape and Analyze Mars Weather Data
1. Open the Jupyter Notebook in the starter code folder named part_2_mars_weather.ipynb. You will work in this code as you follow the steps below to scrape and analyze Mars weather data.
2. Use automated browsing to visit the Mars Temperature Data SiteLinks to an external site.. Inspect the page to identify which elements to scrape. Note that the URL is https://static.bc-edx.com/data/web/mars_facts/temperature.html.
3. Create a Beautiful Soup object and use it to scrape the data in the HTML table. Note that this can also be achieved by using the Pandas read_html function. However, use Beautiful Soup here to continue sharpening your web scraping skills.
4. Assemble the scraped data into a Pandas DataFrame.  
5. Examine the data types that are currently associated with each column. If necessary, cast (or convert) the data to the appropriate datetime, int, or float data types.
6. Analyze your dataset by using Pandas functions to answer the following questions:

    How many months exist on Mars?
    How many Martian (and not Earth) days worth of data exist in the scraped dataset?
    What are the coldest and the warmest months on Mars (at the location of Curiosity)? To answer this question:
    Find the average minimum daily temperature for all of the months.
    Plot the results as a bar chart.
    Which months have the lowest and the highest atmospheric pressure on Mars? To answer this question:
    Find the average daily atmospheric pressure of all the months.
    Plot the results as a bar chart.
    About how many terrestrial (Earth) days exist in a Martian year? To answer this question:
    Consider how many days elapse on Earth in the time that Mars circles the Sun once.
    Visually estimate the result by plotting the daily minimum temperature.
    Export the DataFrame to a CSV file.

