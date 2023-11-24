# scholar_scraper

Code to gather all the papers that cite paper X. 
It crawls through all the citation pages and puts the following information in a json and excel file:
- title
- author
- number of citations
- year
- link to the paper (pdf)
- metadata containing where it was submitted


A second part of the code also extracts the Abstract from pdf links from the sites:
- arxiv.or
- dl.acm.org

Further abstract scraping is left for future work :) 
