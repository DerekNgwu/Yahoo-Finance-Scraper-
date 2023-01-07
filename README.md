# Yahoo-Finance-Scraper-

This script uses the requests library to send an HTTP GET request to the Yahoo Finance website's URL, and the BeautifulSoup library to parse the HTML of the response. It then searches the parsed HTML for the table element containing the cryptocurrency data, and uses the pandas library's read_html function to parse the HTML of the table and create a DataFrame from the data. The DataFrame is then saved to a CSV file using the to_csv method from the pandas library.
