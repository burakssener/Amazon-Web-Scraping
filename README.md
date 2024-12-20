# **Amazon Discount Tracker**

## **Overview**
This project automates the process of tracking your favorite Amazon products for discounts. It constantly monitors product prices and sends you an email notification whenever there is a price drop. The implementation leverages web scraping and automation techniques using Python.

---

## **Features**
- Scrapes Amazon product pages to fetch:
  - Product Name
  - Current Price
  - Product Availability
- Tracks prices over time for selected products.
- Sends email alerts when a price drop is detected.

---

## **Getting Started**

### Prerequisites
- Python 3.x
- Required libraries: `requests`, `BeautifulSoup`, `pandas`, `smtplib`, `schedule`, `time`

### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/burakssener/Amazon-Web-Scraping.git
   ```
2. Install the required dependencies.
   ```bash
   pip install -r requirements.txt
   ```

3. Open the script and configure your email credentials and product URLs.

---

## **How It Works**
1. Add the URLs of your desired Amazon products to the tracker.
2. The script fetches product details and price information periodically.
3. If a price drop is detected, it sends an email alert with product details.

---

## **View the Notebook**
To view the Jupyter Notebook online, use the following link:  
[View on nbviewer](https://nbviewer.org/github/burakssener/Amazon-Web-Scraping/blob/main/AMAZON.ipynb)

*(Replace `YourNotebookName.ipynb` with the actual notebook file name in your repository.)*

---

## **Usage**
1. Update the URLs and set your desired price thresholds.
2. Run the script to start tracking your products.
3. Leave the script running for continuous monitoring.

---

## **Notes**
- Ensure compliance with Amazon's [Terms of Service](https://www.amazon.com/gp/help/customer/display.html?nodeId=508088) when scraping.
- The email credentials used for alerts should be kept secure.

---

If you liked this project or want to discuss anything tech-related, feel free to connect with me:

- 🌐 **Website**: [buraksener.com](https://buraksener.com)  
- 💼 **LinkedIn**: [Burak Sener](https://www.linkedin.com/in/burakssener)
