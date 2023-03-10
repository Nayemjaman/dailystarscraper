# Dailystar news scraper
</hr>

![made-with-python](https://img.shields.io/badge/Made%20with-Python-1f425f.svg)
[![Open in Visual Studio Code](https://img.shields.io/static/v1?logo=visualstudiocode&label=&message=Open%20in%20Visual%20Studio%20Code&labelColor=2c2c32&color=007acc&logoColor=007acc)](https://github.dev/Nayemjaman/dailystarscraper)

</hr>

Welcome to the dailystarscraper repository!

In this project, I scraped news data (from [thedailystar.net](https://www.thedailystar.net)) using scrapy and integrated it with Django. The data is stored in a SQLite database.

Customizations:
- custom scrapy command to run scrapy spiders from django command line. 
``` 
python manage.py news_crawler
```
## Run   

Create a python virtual environment and run these commands from root directory-
```
pip insrall -r requirements.txt
```

This will run the django app-
```
python manage.py runserver
```

NB: Migrate before running the app
```
python manage.py makemigrations && python manage.py migrate
```


## Built With

```
Django==4.1.5
requests==2.28.1
requests-file==1.5.1
Scrapy==2.7.1
scrapy-djangoitem==1.1.1
scrapy-user-agents==0.1.1
service-identity==21.1.0
urllib3==1.26.13
user-agents==2.2.0
lxml==4.9.2
pycparser==2.21
```

## Preview

![Screenshot (147)](https://user-images.githubusercontent.com/40755491/222971951-72d4df5f-6ef8-40d2-a86a-1c15447f6441.png)

![image](https://user-images.githubusercontent.com/40755491/222971868-3e60bbaf-183d-4146-b3f3-500f9f3a7910.png)

![image](https://user-images.githubusercontent.com/40755491/222971790-376f4e98-55f8-483a-9ee8-491d1f88842e.png)


