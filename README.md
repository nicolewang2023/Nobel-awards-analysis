# Nobel-awards-analysis

This project fetches Nobel Prize laureate data via the Nobel Prize API and analyzes the distribution of awards by year and birth country. It includes data normalization, CSV export, and visualizations to reveal country-level trends in Nobel recognition between 2012 and 2022.

## Objective

To explore patterns in global Nobel Prize distribution by analyzing the birth countries of laureates over time. The project demonstrates the use of public APIs, data transformation, and visualization techniques relevant to exploratory data science.

## Features

- API integration with [Nobel Prize API v2.1](https://nobelprize.readme.io/)
- JSON flattening and cleaning using `pandas`
- CSV export for structured data analysis
- Stacked bar chart showing country-level laureate counts by year
- Modular, reusable Python code

## Technologies

- Python
- `requests`
- `pandas`
- `matplotlib`
- Nobel Prize REST API

## How It Works

1. Downloads laureate data from 2012 to 2022 using an API call.
2. Normalizes nested JSON fields into a flat DataFrame.
3. Extracts key metadata: name, gender, birth country, award year, prize category.
4. Saves structured data to a CSV file.
5. Generates a stacked bar chart of Nobel Prizes by birth country and year.

## Installation

```bash
pip install pandas matplotlib requests
