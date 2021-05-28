# Profile Scrapper

## Introduction:
LinkedIn is a Social Networking site with over 750 million users. The User Data is valuable as it can be used to conduct various research. LinkedIn has deployed a strict Anti-Scraping system which makes direct data scraping almost impossible.

The main goal of this project is to develop an algorithm that can bypass anti-scraping algorithms and to extract data of alumni of a particular organization and of a particular domain. Selenium, BeautifulSoup libraries in Python are used. This is used to automate the complete process.

<b>The program scraps user data in a specified domain for the specified institute and stores the scrapped data as a CSV file in your current working directory.</b>

## Libraries:
```bash
# Install Scrapping tolls.
pip install selenium
pip install bs4

# Install api
pip install linkedin_api
```
> :warning: **Run the code only once in a while**.: As the code uses automated browser for scraping, **Google** and **LinkedIn** will detect frequent requests sent from the bot if run several times. Please do not run the code often. Or else **Your LinkedIn account might get banned. If Possible please use a demo linkedin account if available.**

## Output:

#### CSV File:
![Output](https://user-images.githubusercontent.com/72556043/119949709-c2059c00-bfb7-11eb-9940-75122644dacb.png)

