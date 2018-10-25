## Airbnb Spider

# How to run

First time:
`pip install scrapy`

Inside this repo,
`scrapy crawl listing -a query=Austin -o Austin.json`

This is the same as search Austin in the airbnb website and store the raw API result in Austin.json (might contain duplicates)
