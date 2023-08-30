# web_scraping

## Part 1: Scrape Titles and Preview Text from Mars News
- Automated Browsing: In this part, automated browsing tools like Requests were used to visit the Mars news website. This approach simulated a web browser and fetched the content of the webpage.

- Beautiful Soup: To parse the HTML content of the webpage, a Beautiful Soup object was created. Beautiful Soup, a Python library, was employed for web scraping tasks, aiding in navigating and manipulating the HTML structure.

- Inspecting Elements: The HTML structure of the page was examined to identify specific elements (tags and classes) containing the titles and preview text of the news articles.

- Extracting Data: Utilizing Beautiful Soup's methods, data extraction was performed on the identified HTML elements to retrieve the titles and preview text.

- Data Storage: Extracted data was stored in a list of dictionaries. Each dictionary had two keys: 'title' and 'preview'. This organization helped in structuring the scraped information.

- Optional Data Export: Optionally, the scraped data could be exported to a JSON file to facilitate sharing with others.

## Part 2: Scrape and Analyze Mars Weather Data
- Automated Browsing: Similar to Part 1, automated browsing techniques were employed to access the Mars temperature data site.

- Beautiful Soup: Once again, a Beautiful Soup object was created to parse the HTML content and extract pertinent data from the table.

- Data Extraction: The data extraction process involved leveraging Beautiful Soup's capabilities to locate and retrieve the required information from the HTML table.

- Data Analysis: After assembling the data into a Pandas DataFrame, various data analysis tasks were conducted. These included investigating the number of months on Mars, calculating Martian days worth of data, identifying the coldest and warmest months on Mars, determining months with the lowest and highest atmospheric pressure, and estimating the number of terrestrial days in a Martian year.

- Exporting Data: Finally, the DataFrame containing the analyzed data was exported to a CSV file. This file could serve as a record of the obtained insights and findings.
