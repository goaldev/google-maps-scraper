<p align="center">
  <img src="https://www.omkar.cloud/images/favicon/prod/favicon-256x256.png" alt="omkar" />
</p>
  <div align="center" style="margin-top: 0;">
  <h1>✨ Google Maps Scraper 🤖</h1>
  <p>💦 Find New Customers and Grow Your Buisness 💦</p>
</div>
<em>
  <h5 align="center">(Programming Language - Python 3)</h5>
</em>
<p align="center">
  <a href="#">
    <img alt="google-maps-scraper forks" src="https://img.shields.io/github/forks/omkarcloud/google-maps-scraper?style=for-the-badge" />
  </a>
  <a href="#">
    <img alt="Repo stars" src="https://img.shields.io/github/stars/omkarcloud/google-maps-scraper?style=for-the-badge&color=yellow" />
  </a>
  <a href="#">
    <img alt="google-maps-scraper License" src="https://img.shields.io/github/license/omkarcloud/google-maps-scraper?color=orange&style=for-the-badge" />
  </a>
  <a href="https://github.com/omkarcloud/google-maps-scraper/issues">
    <img alt="issues" src="https://img.shields.io/github/issues/omkarcloud/google-maps-scraper?color=purple&style=for-the-badge" />
  </a>
</p>
<p align="center">
  <img src="https://views.whatilearened.today/views/github/omkarcloud/google-maps-scraper.svg" width="80px" height="28px" alt="View" />
</p>

---
  
🌟 Get 120 Potential Customers in 2.5 Minutes! 🤖
Hola! 🌟

I am Google Maps Scraper, created to help you find new customers and grow your sales. 🚀

Why Scrape Google Maps, you may ask? 
Here's why it's the perfect ground for hunting B2B customers:

- 📞 **Direct Access to Phone Numbers**: Connect with potential clients directly, drastically reducing the time it takes to seal a deal.

- 🌟 **Target the Cream of the Crop**: Target rich business owners based on their reviews, and supercharge your sales.

- 🎯 **Tailored Pitching**: With access to categories and websites, you can customize your pitch to cater to specific businesses and maximize your sales potential.

Countless entrepreneurs have achieved remarkable success by prospecting leads from Google Maps, and now it's your turn!

Let's delve into some of my remarkable features that entrepreneurs love:

1. 💪 **Rapid Lead Generation**: I can scrape a whopping **1200 Google Map Leads** in just **25** minutes, flooding you with potential sales prospects.

2. 🚀 **Effortless Multi-Query Scraping**: Easily scrape multiple queries in one go, saving you valuable time and effort.

3. 🌐 **Unlimited Query Potential**: There's no limit to the number of queries you can scrape, ensuring you never run out of leads.

In the next 5 minutes, you'll witness the magic as I extract **120 Leads** from Google Maps for you, opening up a world of opportunities.


![Google Maps Data Scraper CSV Result](https://raw.githubusercontent.com/omkarcloud/google-maps-scraper/master/screenshots/gmap_result.png)

Ready to supercharge your business growth? Let's get started! 💼🌍

## Video Demo 

If you like to see my Capalities in Action before using me. I encourage you to watch this short Video. 

[![Google Maps Video Tutorial](https://raw.githubusercontent.com/omkarcloud/google-maps-scraper/master/screenshots/video.png)](https://www.youtube.com/watch?v=6UZhTlkCb9A)

## 🚀 Getting Started

Let's get startedgenerating Google Maps Leads by following these simple steps

1️⃣ Clone the Magic 🧙‍♀️:
```shell
git clone https://github.com/omkarcloud/google-maps-scraper
cd google-maps-scraper
```
2️⃣ Install Dependencies 📦:
```shell
python -m pip install -r requirements.txt
```
3️⃣ Let the Rain of Google Map Leads Begin 😎:
```shell
python main.py
```

Once the scraping process is complete, you can find your leads in the `output` directory. 

![Google Maps Data Scraper CSV Result](https://raw.githubusercontent.com/omkarcloud/google-maps-scraper/master/screenshots/gmap_result.png)

## 🤔 FAQs

### ❓ The scraper is only retrieving 5 results. How can I scrape all Google Maps search results?
A: Open the file `src/config.py` and comment out the line that sets the `max_results` parameter. 

By doing so, you can scrape all the search results from Google Maps. For example, to scrape all restaurants in Delhi, modify the code as follows:
```python
queries = [
    {
        "keyword": "restaurants in delhi",
        # "max_results" : 5,
    },
]
```
Note: You will be able to scrape up to 120 leads per search due to Google's scrolling limitation. Technically, there is no way possible to bypass this limitation.

### ❓ I want to scrape search results for a specific search query. How can I achieve that?
A: Open the file `src/config.py` and update the `keyword` with your desired search query. 

For example, if you want to scrape leads about Digital Marketers in Kathmandu 🇳🇵, modify the code as follows:
```python
queries = [
    {
        "keyword": "digital marketers in kathmandu",
    },
]
```

### ❓ Can I scrape more than one query using this script?
A: Absolutely! Open `src/config.py` and add as many queries as you like. 

For example, if you want to scrape restaurants in both Delhi 😎 and Bangalore 👨‍💻, use the following code:
```python
queries = [
    {
        "keyword": "restaurants in delhi",
    },
    {
        "keyword": "restaurants in bangalore",
    }
]
```

### ❓ How to Scrape Additional Information like Website, Phone, Geo Coordinates, Price Range?

You may upgrade to Pro Version of the Google Maps Scraper to scrape additional data points, like:

- 🌐 **Website**
- 📞 **Phone Numbers**
- 🌍 **Geo Coordinates**
- 💰 **Price Range**
- And **26 more data points** like Owner details, Photos, About Section, and many more!

Below is a sample lead scraped by the Pro Version:

![Pro Lead](https://raw.githubusercontent.com/omkarcloud/google-maps-scraper/master/screenshots/pro-lead.png)

But that's not all! The Pro Version comes loaded with advanced features, allowing you to:

- 🌟 **Sort by Reviews and Ratings**: Target top businesses by sorting your leads in descending/ascending order of reviews and ratings.

- 🧐 **Filter Your Leads**: Use filters to narrow down prospects based on minimum/maximum reviews, ratings, website availability, and more.

- 📋 **Select Specific Fields**: Customize your data output by selecting only the fields you need, such as title, rating, reviews, and phone numbers.

To learn more about how to use these Pro Version features, read the Pro Version docs [here](https://github.com/omkarcloud/google-maps-scraper/master/pro-docs.md).

🔍 **Comparison**:

See how the Pro Version stacks up against the free version in this comparison image:

![Comparison Image](https://raw.githubusercontent.com/omkarcloud/google-maps-scraper/master/screenshots/comparision-image.png)

And here's the best part - the Pro Version offers great ROI because it helps you land new customers bringing hundreds and thousands of dollars, all with zero risk. That's right because, we offer a **30-Day Refund Policy**!

### ❓ How to Get the Pro Version?

Visit Sponsership Page [here](https://github.com/sponsors/omkarcloud?frequency=one-time) and pay $28 by selecting Google Maps Scraper Pro Option.

![Pay](https://raw.githubusercontent.com/omkarcloud/google-maps-scraper/master/screenshots/pay.gif)

After payment, you'll see a success screen with instructions on how to use the Pro Version:

![Success Screen](https://raw.githubusercontent.com/omkarcloud/google-maps-scraper/master/screenshots/success-screen.png)

### ❓ What if I Don't Get ROI from It?

Your investment is completely risk-free! We stand by our product with a **30-Day Refund Policy**. If you feel that the Pro Version doesn't deliver the value you expected, you can request a refund.

Still unsure about the Google Maps Scraper? No worries! Book a demo meeting, and we'll scrape your chosen places right in front of you

Book a Demo using this [meeting link](https://www.omkar.cloud/l/meet-chetan/).

### ❓ How Do I Get a Refund?

To request a refund, please make sure you have one of the following:

- **A PayPal Account**
- **or A UPI QR Code Image (India only)**
 
Next, Follow these steps to initiate a refund:

1. Visit the Discussion [here] and leave a comment to initiate a refund, with the following template:

   "Please initiate a refund. My communication email is your-email@gmail.com"

   ![Refund Image](https://raw.githubusercontent.com/omkarcloud/google-maps-scraper/master/screenshots/refund-discuss.png)

2. You'll receive an email from `chetan@omkar.cloud` requesting you to provide one of the following details to process the refund:
   - PayPal Email (e.g., your-email@gmail.com)
   - UPI QR Code Image (India Only)

3. After providing the above details you can expect your refund within 2 days, usually within 24 hours. We'll also keep you updated in the GitHub Discussion.

![Paypal Image](https://raw.githubusercontent.com/omkarcloud/google-maps-scraper/master/screenshots/paypal.png)


### ❓ I Need Setup Support for scraper installation and usage?

All Pro users who need assistance with scraper installation and usage can book a meeting with us [here](https://www.omkar.cloud/l/meet-chetan/).

### ❓ How to increase the speed of the Scraper?

To boost the scraping speed, the scraper launches multiple browsers simultaneously. Here's how you can increase the speed furthur:

- Adjust the `number_of_scrapers` variable in the configuration file. Recommended values are:
  - Standard laptop: 4 or 8
  - Powerful laptop: 12 or 16

Note: Avoid setting `number_of_scrapers` above 16, as Google Maps typically returns only 120 results. Using more than 16 scrapers may lead to a longer time spent on launching the scrapers than on scraping the places. Hence, it is best to stick to 4, 8, 12, or 16.

In case you encounter any issues, like the scraper crashing due to low-end PC specifications, follow these recommendations:

- Reduce the `number_of_scrapers` by 4 points.
- Ensure you have sufficient storage (at least 4 GB) available, as running multiple browser instances consumes storage space.
- Close other applications on your computer to free up memory.

Additionally, consider improving your internet speed to further enhance the scraping process.


### ❓ How much time does it take to scrape "n" searches?

On average, each Google Maps search gives 120 listings. It takes approximately 2.5 minutes to scrape these 120 listings.

To calculate the number of **hours** it takes to scrape "n" searches, you can **google search** this formula substituting `n` with number of searches you want to conduct:

`n * 2.5 minutes`

For example, if you want to scrape 10 google map queries or 1200 listings, it will take around 25m.

![](https://raw.githubusercontent.com/omkarcloud/google-maps-scraper/master/screenshots/search-time.png)

### ❓ How to Run it in Docker?

1. Run the following command to build Docker Image:
   ```
   docker-compose build
   ```
2. Run the following command to start the Conatiner:
   ```
   docker-compose up
   ```
## 🤔 Have Questions

Ask them in discussions [here](https://github.com/omkarcloud/google-maps-scraper/discussions/), and you will receive a guaranteed response within 24 hours.

## Love It? [Star It! ⭐](https://github.com/omkarcloud/google-maps-scraper)

[![Stargazers for @omkarcloud/google-maps-scraper](https://reporoster.com/stars/omkarcloud/google-maps-scraper)](https://github.com/omkarcloud/google-maps-scraper/stargazers)
