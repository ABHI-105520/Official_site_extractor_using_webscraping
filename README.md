# Official_site_extractor_using_webscraping
---
This project is about scraping web search results and fetch the official websites of companies. To automate search and scrap, duckduckgo API is used as it doesn't require API key or CSE ID. The first result of the search is fetched as the official website are always the first url. After fetching the url, it has to be verified whether the url is genuinely the official or not. So the logic here is either,

1. The whole company name is present in domain name.
2. The first word of the company name is present in domain name.
3. The Initials of the Company name is present in the domain name.
If none of the condition is matched, the result is not an official website of the searched name.

Here are two different codes,
scrap_official_websites
In this code, the company names are read from company_name.csv. Then scrapped and return the official website if available.

search_official_website
In this code, the company names are taken from user input. Then scrapped and return the official website if available.
