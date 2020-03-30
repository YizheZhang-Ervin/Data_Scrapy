# EZScrapy
Scrapy

## Install:
    pip install scrapy  
    scrapy -h  
    
## Components(5+2):
    1) Spiders[Entrance]  
    2) Downloader  
    3) Scheduler  
    4) Itempipelines  
    5) Engine  
    1&5) Spider Middleware  
    2&5) Downloader Middleware  
    
    Sequence:1-5-3-5-2-5-1-5-4  
    
## Steps:
    scrapy command options args  
    scrapy startproject name dir  
    scrapy genspider options spidername domain  
    scrapy crawl spidername  
    scrapy settings options  
    scrapy list  
    scrapy shell url  
    
## Gain Information Methods:
    BeautifulSoup  
    lxml  
    re  
    xPath Selector  
    CSS Selector  
    
## Settings:
    CONCURRENT_REQUESTS: 32 default  
    CONCURRENT_ITEMS: 100 default  
    CONCURRENT_REQUESTS_PER_DOMAIN: 8 default  
    CONCURRENT_REQUESTS_PER_IP: 0 default  