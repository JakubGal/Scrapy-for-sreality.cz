# Task
Use scrapy framework to scrape the first 500 items (title, image url) from sreality.cz (flats, sell) and save it in the Postgresql database. Implement a simple HTTP server in python and show these 500 items on a simple page (title and image) and put everything to single docker compose command so that I can just run "docker-compose up" in the Github repository and see the scraped ads on http://127.0.0.1:8080 page.

# Usage 
1. Run "docker-compose up"
2. Open http://127.0.0.1:8080 in your favorite browser

# Creadit
Hardly based on this repository with few things fixed:
https://github.com/Honzama/sreality-scrapy-task