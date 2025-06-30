# amazon-price-tracker

Amazon Price Tracker (Python)

This project is a simple Amazon product price tracker built with Python. It scrapes the price of a specified product and logs it to a CSV file. If the price drops below your target, it sends an email notification.


Features

- Scrapes product title and current price from Amazon
- Appends daily data to a CSV file
- Sends email alerts using Gmail SMTP if the price drops
- Easy to schedule using Task Scheduler or Cron


Technologies Used

- Python 3
- `requests` and `BeautifulSoup` for web scraping
- `csv` and `datetime` for logging
- `smtplib` for sending emails

 How It Works

1. Set your target price in the script.
2. Run the `check_price()` function.
3. The script:
   - Scrapes the product page
   - Logs the title, price, and date
   - Sends you an email if the price is below your target

