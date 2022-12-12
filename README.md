# Mission_to_Mars

## Aim
The aim of this project is to apply full web-scraping for the mission to Mars by collecting data, organizing and storing data, analyzing data, and then visually communicating our insights.

## Analysis of Data and Results
1. Scrape Titles and Preview Text from Mars News

Using Splinter an automated browsing was used to visit the Mars news site. Then, extracted the HTML code with Beautiful Soup and scrapedextracted the titles and preview text of the news articles.Finally, we have exported the data to JSON file and we have saved them as "Data/mars_data"

2. Scrape and Analyze Mars Weather Data
Using Splinter an automated browsing was used to visit the Mars temperature data site. Extracted the HTML code with Beautiful Soup and scraped/extracted the Mars temperature table into a Pandas DataFrame, cleaned the table data by editing its data types.

After extracting Mars temperature table, analyzed and visualized the data by finding answers to the following questions:<br>

How many months exist on Mars? <br>
Which month, on average, has the lowest temperature? The highest? <br>
Which month, on average, has the lowest atmospheric pressure? The highest? <br>
How many terrestrial days exist in a Martian year? <br>

Finally, the last step was to export our data as mars_table.csv
