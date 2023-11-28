# Task
Use scrapy framework to scrape the first 500 items (title, image url) from sreality.cz (flats, sell) and save it in the Postgresql database. Implement a simple HTTP server in python and show these 500 items on a simple page (title and image) and put everything to single docker compose command so that I can just run "docker-compose up" in the Github repository and see the scraped ads on http://127.0.0.1:8080 page.

# Usage 
1. Run "docker-compose up"
2. Open http://127.0.0.1:8080 in your favorite browser

I should look something like this: Image of website
![Image of website](https://github.com/JakubGal/Scrapy-for-sreality.cz/assets/44644846/5d7c738e-2c15-4250-9c70-749a2569b5ee)

# Credit
Hardly based on this repository with few things fixed:
https://github.com/Honzama/sreality-scrapy-task
