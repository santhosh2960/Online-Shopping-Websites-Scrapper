# scrapy_python (amazon_jabong_scrapper)

amazon_jabong_scrapper is a scrapper script written in Python using Scrapy framework to scrape data from two ONLINE SHOPPING WEBSITES, Amazon and Jabong websites. The primary purpose is to RETRIEVE AND COMPARE CLOTHING PRODUCTS from both of them and perform analytics on the same. This is a very old script written in 2016. This might not work well now as the structure of these websites might have been changed.

Sample Json Output: https://raw.githubusercontent.com/santhoshraj2960/amazon_jabong_scrapper/jabong_scrapper/jabong_scrapper/jabong_scrapper/jabong_items13.json

Since I had this repo committed inside my other github account(https://github.com/santhosh2960) for which I lost access, I have committed it freshly from this new account.

The script scrapes information such as

Title of the listed products
Sizes available for those products
Links to the other relevenet products recommended by Amazor or Jabong
Prices and Sellers available for the product
Description of the product such as colour, texture, etc
The complete sub category of the product such as (Fashion -> Men's Fashion -> T-shirts -> Round neck -> Full sleeve)
The scipt then saves the data into a Json file. ex: https://raw.githubusercontent.com/santhoshraj2960/amazon_jabong_scrapper/jabong_scrapper/jabong_scrapper/jabong_scrapper/jabong_items13.json
Requirements:

Scrapy 1.7
Python 2.7
Regex 3.7
A list of proxy ips
