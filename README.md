# Live-Forex-Top-10-Scraper
Overview:
This Python project fetches live forex exchange rates from a public API (Frankfurter) and dynamically selects the top 10 currencies relative to a chosen base currency. The project demonstrates: a.Live data scraping | b.Autonomous selection of top currencies | c.Timestamped output | d.Historical data collection for future analysis

Features: a.Fetches live forex rates for all available currencies from the Frankfurter API. | b.Dynamically determines the top 10 currencies based on their current rate relative to the base currency. | c.Outputs rates with a timestamp for tracking.

Can be extended to: a.Store data in CSV for historical tracking. | b.Compute percentage changes / returns. | c.Generate time-series plots of currency trends. | d.Automate fetching at custom intervals (every 12 hours).

Requirements: a.Python 3.8 or higher | b.requests library | c.Optional (for analysis and plotting): pandas, matplotlib

Install dependencies using: pip install requests pandas matplotlib

Notes: a.This project uses Frankfurter API, which is free and publicly accessible. | b.The script currently fetches a snapshot of live rates; graphs and analysis become meaningful as more data is collected over time. | c.You can change the base currency in the script (default is USD) if you want to track rates relative to another currency.
