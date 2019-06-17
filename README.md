# Crawler

Web crawler using scrapy.

## Installing / Getting started

Clone the repository, then install prerequisites.

```shell
pip install scrapy
pip install pymongo
```

Install scrapy.
 
## Usage

```shell
mongod
scrapy crawl [SPIDER]
```

Make sure the Mongo daemon is running, then run spider to crawl through webpages.

```shell
mongo
```

Open the mongo shell.

```
show dbs
use stackoverflow
show collections
db.questions.count()
db.questions.find()
```

Some useful commands for viewing your data.
