Python 3.6.6

Ready scraper reviews of products from Amazon.
You can change the scraping of all reviews for reviews for a certain year by changing the code in the amazon_spider.py file(the code comments show how to do this).


scrapy crawl amazon-reviews-spider -a product_id=XXXXXXXX                                 
example product id B074VLX5XV                                               
scrapy crawl amazon-reviews-spider -a product_id=B074VLX5XV                                     
