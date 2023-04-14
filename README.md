# Python_Crawling_Flightickets

git clone https://github.com/htzhu/Python_Crawling_Flightickets.git

'''
ITEM_PIPELINES = {
    'findtrip.pipelines.MongoDBPipeline': 300,
}

MONGODB_HOST = 'localhost' # Change in prod
MONGODB_PORT = 27017 # Change in prod
MONGODB_DATABASE = "findtrip" # Change in prod
MONGODB_COLLECTION = "qua"
MONGODB_USERNAME = "" # Change in prod
MONGODB_PASSWORD = "" # Change in prod
'''

scrapy crawl Qua

scrapy crawl Ctrip

scrapy crawlall
