# Ad_Scraper
Scraping Ads from websites and identifying the content and logo in them <br>


### How to Run
To run this program you would have to have the following packages installed <br>

pip install requests <br>
pip install webdriver_manager <br>
pip install bs4 <br>
pip install opencv <br>
pip install urllib <br>
pip install PIL <br>
pip install matplotlib <br>
pip install pytesseract <br>
pip install selenium <br>
pip install easyocr <br>

### How to run make this work for different websites
Currently I am scraping ads of only "https://www.speedtest.net/". <br>
To change this, change the URL on cell number 4. <br>
Also change the frame in which the ads are present. <br>


### What I have done till now:
I have extracted ads from the website <br>
Applied OCR to the ad images and extracted the text in those images <br>
Used flickr_logos_27_dataset to train the model for logo identification <br>
