# Nepal Adel Aly

Data Engineer based in Alexandria, Egypt. I build data pipelines that collect, clean and model data, then load it into databases and reports that people can use.

I am currently in the DEPI program (Digital Egypt Pioneers Initiative, Round 5, Microsoft Data Engineer track).

---

## What I Work With

| Area | Skills |
|---|---|
| Languages | Python, SQL |
| Data processing | Pandas, PySpark, Delta Lake |
| Data collection | Web scraping (requests, BeautifulSoup, Selenium), REST APIs |
| Databases | PostgreSQL, SQLite, MySQL |
| Data modeling | Star schema, Medallion architecture (Bronze, Silver, Gold) |
| Reporting | Power BI, Excel |
| Workflow | Git, GitHub, Docker, Jupyter Notebook, pytest |

---

## Projects

### Egypt Smartphone Price Tracker

[Repository](https://github.com/nepal-aly/egypt-smartphone-price-tracker)

An ETL pipeline that collects smartphone prices from Egyptian online stores to compare prices and track them over time. The Jumia Egypt extractor is done: 1,848 smartphones across 47 pages, with 18 columns per product (price, old price, discount, rating, seller and more). It reads the product data embedded in each page instead of parsing the HTML cards, retries failed pages and follows the site's robots.txt rules. The cleaning step is also done for Jumia: it turns text prices into numbers, removes 19 non-phone products, unifies brand names, and extracts storage and RAM from the product names, leaving 1,829 clean phones with 22 columns.

Stack: Python, requests, BeautifulSoup, Pandas, SQLite, Jupyter Notebook.

### Beauty Products Data Pipeline

[Repository](https://github.com/nepal-aly/beauty-products-pipeline)

An end-to-end ETL pipeline that extracts makeup and perfume data from two public APIs (Makeup API and Open Beauty Facts), cleans it with Pandas and loads it into SQLite and Excel.

| Table | Rows before cleaning | Rows after cleaning |
|---|---|---|
| makeup_products | 931 | 916 |
| makeup_colors | 5,329 | 5,254 |
| makeup_tags | 419 | 378 |
| beauty_products | 1,400 | 1,308 |
| Total | 8,079 | 7,856 |

Cleaning covered brand names, HTML codes in product names, duplicates, text prices, invalid color codes and product sizes written in many formats.

Stack: Python, requests, Pandas, SQLite, SQL, Excel.

### Python Practice Projects

Object-oriented Python projects built with Turtle graphics:

- [Middle East Map Game](https://github.com/nepal-aly/middle-east-map-game): a map quiz that reads country data from CSV with Pandas.
- [Snake Game](https://github.com/nepal-aly/snake-game-python)
- [Ping Pong](https://github.com/nepal-aly/ping-pong-python)
- [Shape Catcher](https://github.com/nepal-aly/shape-catcher-game)

---

## Certificates

| Certificate | Issuer | Date |
|---|---|---|
| Database Fundamentals | ITI Mahara-Tech | September 2026 |
| AI for You (badge) | Oracle | August 2026 |
| Microsoft Data Engineer track (in progress) | DEPI, Round 5 | Since June 2026 |

---

## Education

Bachelor of Commerce, Damanhour University (2022 - 2026)

---

## Work With Me

I take freelance work in data cleaning, web scraping, Python, SQL and Excel reports. You can see my services and reviews on:

| Platform | Profile |
|---|---|
| Khamsat | [nepal_aly](https://khamsat.com/user/nepal_aly) |
| Nafezly | [nepaladel](https://nafezly.com/u/nepaladel) |
| Mostaql | [Nepal_Aly](https://mostaql.com/u/Nepal_Aly) |
| Freelancer | [nepalali](https://www.freelancer.com/u/nepalali) |

---

## Contact

- LinkedIn: [nepal-aly-data](https://www.linkedin.com/in/nepal-aly-data)
- GitHub: [nepal-aly](https://github.com/nepal-aly)
