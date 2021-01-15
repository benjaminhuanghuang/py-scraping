# Python Scraping



## Setup
```
  python3 -m venv venv3
  
  pip install Scrapy

  scrapy --help

```
## create a template
```
  scrapy startproject ietf_scraper
  
  http://pythonscraping.com/linkedin/ietf.html

  cd ietf_scraper/ietf_scraper/spiders/

  scrapy genspider xxx exmaple.com
```

## run scrapy
```
   scrapy runspider test.py
```


## CrawlSpider sample
```
  scrapy startproject article_scraper

  cd article_scraper/article_scrapers/spiders/

  scrapy genspider wikipedia en.wikipedia.org
```


