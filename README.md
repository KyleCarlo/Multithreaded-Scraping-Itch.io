# Web Scraping

This repository contains the source code focusing on web scraping. The project involves extracting data from a specified website, in this case, itch.io, to create a dataset of indie games.

# Collaborators

- Kyle Carlo Lasala
- Katrina Bianca Roco
- Antonio Jose Maria Lorenzo
- Charles Joseph Hinolan

# Methodology

The notebook outlines a step-by-step process for multithreaded web scraping:

1. Library Imports: All necessary libraries are imported at the beginning.

2. Web Scraping: The core logic uses a combination of Selenium and Requests, along with multithreading, to navigate itch.io and gather data on various games, including their titles, authors, genres, and other relevant details, more efficiently.

3. Data Parsing: Beautiful Soup is employed to parse the raw HTML data and extract the required information cleanly.

4. Data Storage: The extracted data is then structured and stored, likely in a Pandas DataFrame, for further analysis and eventual export.

This project demonstrates a practical application of web scraping techniques for data collection, a fundamental skill in data science and analysis.

