# Decisão Imóveis Scraping

## Overview
This repository contains a Python script for web scraping real estate listing information from the [Decisão Imóveis website](https://decisaoimoveis.com.br). The script is written in Python and uses Beautiful Soup for parsing HTML content.

## Features
- Extracts URLs of real estate listings from Decisão Imóveis website.
- Saves the extracted URLs to a `.txt` file for further processing.
- Initializes a `.csv` file to store detailed property information such as code, title, neighborhood, address, internal and external area, number of bedrooms, bathrooms, suites, parking spaces, IPTU (property tax), condominium fees, and price.

## Requirements
- Python 3.x
- Beautiful Soup 4
- Pandas
- urllib
- tqdm
- re (regular expression library)
