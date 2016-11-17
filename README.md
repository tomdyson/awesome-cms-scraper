# awesome-cms-scraper

Scrapes https://github.com/postlight/awesome-cms, which scrapes Github for a curated set of CMSs, and serve a list ordered by GH stars, via [Chalice](https://github.com/awslabs/chalice), to https://releases.wagtail.io/ranking.html. Will break easily.

## Installation

- `git clone https://github.com/tomdyson/awesome-cms-scraper.git`
- `cd awesome-cms-scraper`
- `pip install chalice`
- `pip install -r requirements.txt`
- add [AWS credentials](https://github.com/awslabs/chalice#credentials) if you haven't already
- try it out: `chalice local`
- deploy: `chalice deploy`
