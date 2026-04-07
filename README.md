# Wall Paint Scraper

## Project Overview
This project implements a web scraper to extract comprehensive product data for 'wall paint' listings from Amazon. The collected data is then cleaned, processed, and saved into a CSV file, providing valuable market intelligence for paint companies.

## Value Proposition
This tool serves as a **Market Intelligence Scraper** for paint industry stakeholders. It provides strategic insights through:
*   **Competitive Analysis:** Monitor competitor pricing and product offerings.
*   **Market Trend Identification:** Identify emerging trends in paint types, brands, and customer preferences.
*   **Pricing Strategy:** Inform optimal pricing strategies based on market data.
*   **Product Development Insights:** Understand customer sentiment and identify areas for product improvement or new product development.
*   **Customer Sentiment Analysis:** Analyze ratings and reviews to gauge customer satisfaction and pain points.

## Features
*   **Targeted Scraping:** Specifically designed to scrape 'wall paint' product listings from Amazon.
*   **Detailed Data Extraction:** Collects key product attributes including:
    *   Product Title
    *   Price (raw and numeric)
    *   Customer Rating (raw and numeric)
    *   Number of Reviews (raw and numeric)
    *   Availability Status and Flag
    *   Inferred Paint Base Type (Oil-Based, Water-Based, Unknown)
    *   Brand
    *   Category
    *   Product URL
    *   Scrape Date
*   **Data Cleaning & Preprocessing:** Handles missing values, converts data types, and infers product attributes where possible.
*   **Output:** Saves the scraped and processed data into a clean CSV file (`amazon_paint_data.csv`).
