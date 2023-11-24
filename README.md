# Google Scholar Scraper

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


 ---------------
 For an example see "citation_data" folder.
These citations are from the page: 

https://scholar.google.com/scholar?start=0&hl=nl&as_sdt=2005&cites=14566886582099332396&scipsc=
