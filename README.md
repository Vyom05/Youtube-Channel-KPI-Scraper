# Youtube-Channel-KPI-Scraper

A Python automation tool to extract YouTube channel names and links from search results using Selenium, check for duplicates in an existing dataset (`Influencers.xlsx`), and enrich the new entries with subscriber count and video count. The final output is saved as an Excel file.

---

## Features

- Scrapes YouTube search results for channel names and links  
- Compares with an existing Excel database to skip duplicates  
- Fetches number of videos and subscribers for each new channel  
- Saves the enriched new entries to a new Excel file  

---

## Example Use Cases

- Influencer outreach databases  
- Social media market research  
- Competitor analysis for YouTube creators  
- Building data pipelines for YouTube analytics  

---

## Requirements

Install these Python packages before running the script:

```bash
pip install selenium pandas openpyxl
