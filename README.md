**My Tracker for beauty products- Web scraping using python**

![Screenshot 2024-03-28 at 22 25 55](https://github.com/kavya2693/Webscraping-with-scheduling/assets/127579722/df6dbfe3-906b-4aef-a483-8183ab249236)

Hey all, I worked on a webscraping code for extracting data to receive updates on price and ratings my favourite beauty products across various online websites in USA.

**Overview:**

Who doesn’t want a update on the most sought after products especially during sale season just with a single click?

This project is designed to track the price changes and ratings of selected beauty products across various prominent online retailers in the USA. Utilizing the power of web scraping and data formatting this tool provides daily updates, allowing me to monitor market trends and make informed decisions, especially during the sale season.

**Features:**

**Daily Updates:** Automated scraping is scheduled to run every day, ensuring the most current data is always available.

**Comprehensive Coverage:** Tracks products from multiple online retailers, including Kohls, Lovelyskin, Skinlovecream, Walgreens, and Ultabeauty.

**Data Insights:** Captures not only the price but also the product ratings, offering a more nuanced view of the market.

**Historical Data:** By accumulating data over time, the tool can offer insights into pricing trends and rating fluctuations.

**How It Works:**

The script is scheduled to execute daily scraping tasks using the Python schedule module. It targets specific product pages on each retailer's website, extracting information about the product's name, current price, and customer ratings. This data is then formatted and displayed in a structured table, making it easy for users to review and analyze.

**Customizable Scheduling:**

The script is scheduled to run at a specific time each day, but you can easily adjust this to suit your needs. Whether you prefer early morning updates or evening summaries, the scheduling feature is fully customizable.

Simply modify the **schedule.every().day.at("22:00:00").do(combined_scrape)** line in the script to the time that best fits your schedule, ensuring you receive updates at your convenience.

**Data Example:**

Below is a snapshot of the type of data the script collects:

![Screenshot 2024-03-28 at 22 27 06](https://github.com/kavya2693/Webscraping-with-scheduling/assets/127579722/8a13e19c-162a-41ed-9387-e46e17cafa25)

**Setup and Usage:**

To set up this project, clone the repository to your local machine or server and install the required Python packages:

**pip install requests beautifulsoup4 schedule tabulate**

To initiate the scraping process, run the script:

**scrape_beauty_products.py**

The script will then automatically perform daily scrapes at the scheduled time, collecting and displaying the latest data.

**Note:**

This project is connected to a server that allows for uninterrupted daily execution, ensuring that data is consistently up-to-date. Users should ensure their server settings prevent the system from sleeping or shutting down, which could interrupt the scheduled tasks.

**Conclusion:**

By providing daily insights into price changes and ratings, this project empowers users to track their favorite beauty products' market behavior, optimizing their purchasing decisions during key shopping periods.

**Ethical Consideration**

When using this tool, please be mindful of the ethical implications associated with web scraping. Ensure that your scraping activities comply with the terms of service of the target websites and respect any guidelines they have regarding automated access. Responsible use of this tool is crucial to uphold ethical standards and maintain the integrity of the data collection process, contributing to a respectful and lawful online environment.

Hope this helps!!

![Screenshot 2024-03-28 at 22 26 22](https://github.com/kavya2693/Webscraping-with-scheduling/assets/127579722/22c78ddd-2193-4ae4-946b-e58d628b1b73)


