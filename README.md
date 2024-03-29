**My monitoring list for beauty products- Web scraping using python**
<img width="581" alt="image" src="https://github.com/kavya2693/Webscraping/assets/127579722/474d5318-0910-44c0-99eb-8bc42c1fa985">

I worked on webscraping, data formatting, and data analysis **to receive updates on price changes of my favorite beauty products across various online websites in USA. **

Beauty Product Price Tracker
Overview
This project is designed to track the price changes and ratings of selected beauty products across various prominent online retailers in the USA. Utilizing the power of web scraping, data formatting, and data analysis, this tool provides daily updates, allowing users to monitor market trends and make informed decisions, especially during the sale season.

Features
Daily Updates: Automated scraping is scheduled to run every day, ensuring the most current data is always available.
Comprehensive Coverage: Tracks products from multiple online retailers, including Kohls, Lovelyskin, Skinlovecream, Walgreens, and Ultabeauty.
Data Insights: Captures not only the price but also the product ratings, offering a more nuanced view of the market.
Historical Data: By accumulating data over time, the tool can offer insights into pricing trends and rating fluctuations.
How It Works
The script is scheduled to execute daily scraping tasks using the Python schedule module. It targets specific product pages on each retailer's website, extracting information about the product's name, current price, and customer ratings. This data is then formatted and displayed in a structured table, making it easy for users to review and analyze.

Data Example
Below is a snapshot of the type of data the script collects:

Scraping started for Kohls, Lovelyskin, Skinlovecream, Walgreens, Ultabeauty at 2024-03-29 01:43:58

╒════════════════════════════════════════════════════════════╕
│ Product Name                                               │ Price   │ Rating │
╞════════════════════════════════════════════════════════════╡
│ Olaplex No. 7 Bonding Hair Oil Size: 1.0 oz                │ $30.00  │  4.3   │
│ Olaplex No. 4 Bond Maintenance Shampoo 8.5 fl oz           │ $30.00  │  4.2   │
...
╘════════════════════════════════════════════════════════════╛
Scraping ended at 2024-03-29 01:44:19
![Screenshot 2024-03-28 at 22 09 46](https://github.com/kavya2693/Webscraping-with-scheduling/assets/127579722/54c049b6-4bd3-475d-bcea-eed436fea638)

**Setup and Usage
**
To set up this project, clone the repository to your local machine or server and install the required Python packages:

pip install requests beautifulsoup4 schedule tabulate

To initiate the scraping process, run the script:

python scrape_beauty_products.py


The script will then automatically perform daily scrapes at the scheduled time, collecting and displaying the latest data.

Note
This project is connected to a server that allows for uninterrupted daily execution, ensuring that data is consistently up-to-date. Users should ensure their server settings prevent the system from sleeping or shutting down, which could interrupt the scheduled tasks.

Conclusion
By providing daily insights into price changes and ratings, this project empowers users to track their favorite beauty products' market behavior, optimizing their purchasing decisions during key shopping periods.
