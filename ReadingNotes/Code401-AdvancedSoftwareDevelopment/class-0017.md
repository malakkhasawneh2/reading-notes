## What is WebScraping? 
    Web scraping, web harvesting, or web data extraction is data scraping used for extracting data from websites. 
    It is a task that has to be performed responsibly so that it does not have a detrimental effect on the sites being scraped. 
    Web Crawlers can retrieve data much quicker, in greater depth than humans, 
    so bad scraping practices can have some impact on the performance of the site. 
    While most websites may not have anti-scraping mechanisms, some sites use measures that can lead to web scraping getting blocked,
    because they do not believe in open data access.

## Web Scraping best practices to follow to scrape without getting blocked
    1-  Respect Robots.txt
    2-  Make the crawling slower, do not slam the server, treat websites nicely
    3-  Do not follow the same crawling pattern
    4-  Make requests through Proxies and rotate them as needed
    5-  Rotate User Agents and corresponding HTTP Request Headers between requests
    6-  Use a headless browser like Puppeteer, Selenium or Playwright
    7-  Beware of Honey Pot Traps
    8-  Check if Website is Changing Layouts
    9-  Avoid scraping data behind a login
    10- Use Captcha Solving Services

## How can websites detect and block web scraping?
    1-  Unusual traffic/high download rate especially from a single client/or IP address within a short time span.
    2-  Repetitive tasks performed on the website in the same browsing pattern – based on an assumption that a human user won’t perform the same repetitive tasks all the time.
    3-  Checking if you are real browser – A simple check is to try and execute javascript. 
    Smarter tools can go a lot more and check your Graphic cards and CPUs to make sure you are coming from real browser.
    4-   Detection through honeypots – these honeypots are usually links which aren’t visible to a normal user but only to a spider. 
    When a scraper/spider tries to access the link, the alarms are tripped.
