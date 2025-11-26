# vgchartzScrape (fork)

This repository is a fork of [GregorUT/vgchartzScrape](https://github.com/GregorUT/vgchartzScrape).

The original project provides a Python script that scrapes game sales data from  
http://www.vgchartz.com/gamedb/ using BeautifulSoup and writes the results to `vgsales.csv`.

This fork mainly exists to make the script work in my environment and to do some experiments.

## Changes in this fork

- Updated the scraping code to work in my context (e.g. Python 3 / `urllib.request`)
- Added more robust scraping with retries and per-page backup CSV files
- Cleaned up the repository layout (e.g. `.gitignore`, removing generated outputs)
- Added a small test script for experimenting with the scraping logic

## Requirements

You’ll need:

- `beautifulsoup4`
- `pandas`
- `numpy`

Install them with:

```bash
pip install beautifulsoup4 pandas numpy
