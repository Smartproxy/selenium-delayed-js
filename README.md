<p align="center">
    <a href="https://smartproxy.com/"><img src="https://images.prismic.io/smartproxy/400e44d6-09ea-4168-a848-ed0e7cfb442a_sp-logo-dark-vertical.png" alt="Smartproxy logo" width="200"></a>
  </a>
</p>

[<img src="https://i.ibb.co/S6ytt21/github-banner.png">](https://dashboard.smartproxy.com/register?coupon=SMARTHUB20&utm_source=github&utm_medium=referral&utm_campaign=repository&utm_content=banner)

## Dependencies

```http
bs4
webdriver_manager
selenium
extension >> extension.py
```

## Authentication

You can create, edit, and delete proxy users in our Dashboard > Residential > Proxy setup page.

## Delayed JS Selenium Scraper

This code is a script in Python that uses the selenium and BeautifulSoup libraries to scrape delayed Javascript elements.

The script uses the Chrome web browser, controlled by the selenium library, to navigate to the website and retrieve its source code. The source code is then parsed using BeautifulSoup to extract specific information.

In order to use a proxy, the code uses the "webdriver_manager" and "extension" libraries to install the chrome driver and configure the Chrome browser to use a proxy server. The credentials for the proxy server, username, password, endpoint, and port are passed as arguments to the "proxies" function from the "extension" library (extension.py).

