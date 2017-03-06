Reddit Article Scrape
=====================

small python program that requests reddit json data, parses, and returns to browser as well as sends you an email.

The program also includes the links of each article, internal or external.

### Getting Started

```bash

# be sure you have pip and python 2.7+ installed

# create a virtualenv
virtualenv venv
source venv/bin/activate

# install requirements
pip install -r requirements.txt
```

Initialize the Database

```bash
zacmimi@macbook ~/personal_projects/reddit_article_scrape $ python manage.py shell

>>> from reddit_article_scrape import db
>>> db.create_all()
```

Start the Dev Server

```
python manage.py runserver
```

View it in your browser http://localhost:5000
