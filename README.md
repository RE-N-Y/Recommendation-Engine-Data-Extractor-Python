# Recommendation-Engine-Data-Extractor-Python

### Scrapy extractor for myanimelist data

A python implementation of a web scraper using scrapy package in python. The /spiders directory contains the spiders for
extracting features such as descriptions and user metadata. Timeouts were set for each request to respect rate limiting of
the source website. In order to start the spiders please use "scrapy runspider [spider_name]" command in the terminal.
The output is a json data which contains json objects for each line
