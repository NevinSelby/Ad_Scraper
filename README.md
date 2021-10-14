## Ad_Scraper
Scraping Ads from websites and identifying the content and logo in them


# How to Run
To run this program you would have to have the following packages installed

pip install requests
pip install webdriver_manager
pip install bs4
pip install opencv
pip install urllib
pip install PIL
pip install matplotlib
pip install pytesseract
pip install selenium
pip install easyocr

# How to run make this work for different websites
Currently I am scraping ads of only "https://www.speedtest.net/".
To change this, change the URL on cell number 4.
Also change the frame in which the ads are present.


# What I have done till now:
I have extracted ads from the website
Applied OCR to the ad images and extracted the text in those images
Used flickr_logos_27_dataset to train the model for logo identification
