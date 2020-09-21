# Automatic Udemy Course Enroller: GET PAID UDEMY COURSES for FREE
Do you want to LEARN NEW STUFF for FREE? Don't worry, with the power of web-scraping and automation, this script will find the necessary Udemy Coupons &amp; enroll you for PAID UDEMY COURSES, ABSOLUTELY FREE!

The code scrapes course links and coupons from [tutorialbar.com](https://tutorialbar.com)

In case of any bugs or issues, feel free to ping me on [Twitter](https://twitter.com/Antariksh_Patre)

***Video Proof:***

[![Udemy Auto-Course-Enroller](https://img.youtube.com/vi/bnqLOncUrw0/0.jpg)](https://www.youtube.com/watch?v=bnqLOncUrw0 "GET PAID UDEMY Courses for FREE, Automatically with this Python Script!")

---

## Requirements:
<ul>
  <strong><li>Requests module for Python:</li></strong>
<pre><code>pip install requests</code></pre>

<strong><li>BeautifulSoup Web-Scraping Library for Python:</li></strong>
<pre><code>pip install pip install beautifulsoup4</code></pre>

<strong><li>Selenium Browser Automation Tool  for Python:</li></strong>
<pre><code>pip install selenium</code></pre>

<strong><li>Required Python version:</strong> [Python 3.8](https://www.python.org/downloads/release/python-380/)</li>

<strong><li>A webdriver for the browser of your choice:</strong> 
<ul>
  <li>Edge- https://developer.microsoft.com/en-us/microsoft-edge/tools/webdriver/</li>
  <li>Chrome- https://chromedriver.chromium.org/</li>
  <li>Firefox- https://github.com/mozilla/geckodriver/releases</li>
  <li>Safari- https://webkit.org/blog/6900/webdriver-support-in-safari-10/ .etc</li>
</ul>

<strong>Note:</strong> Make sure that the driver version matches your browser.</li>
</ul>

---

## Instructions
<ol>
  <li>Make sure to install all the requirements above.</li>
  <li>Choose either format of the code: the .py file (highly recommended) or the jupyter notebook (untested).</li>
  <li>Open the .py file in IDLE. Then click on <strong>Options->Show Line Numbers</strong> in the IDLE Menu Bar.</li>
  <li>Enter your Udemy credentials in the <strong>email</strong> & <strong>password</strong> variables on line 43 & 44 of the code.</li>
  <li>Enter the location of you webdriver in the path variable on line 52.</li>
  <li>Choose the appropriate browser in the driver variable on line 53.</li>
  <li>The bot starts scraping the course links from the first <strong>All Courses</strong> page on <a href='https://www.tutorialbar.com/all-courses/page/1'>Tutorial Bar</a> and starts enrolling you to Udemy courses. After it has enrolled you to courses from the first page, it then moves to the next Tutorial Bar page and the cycle continues. However, you can change the starting page in the <strong>page</strong> variable on line 121. (not recommended, except when you are trying to redeem old coupons, which may or may not be valid at this point of time; But sometimes, by a stroke of luck, the coupons may still work!)</li>
</ol>

---

## FAQs

### Can I get a specific course for free with this script?
Unfortunately no, but let me assure you that you may be lucky enough to get a particular course for free when the instructor posts it's coupon code in order to promote it. Also, over time you would build a library of courses by running the script often and have all the required courses in your collection. In fact, I made this course after completing a [Python automation course](https://www.udemy.com/course/automate/) and selenium, which of course I got for free! :)

### How frequently should you run the script?
Daily, at least once! If you are using it for the first time, I recommend that you allow it to scrape through all pages on Tutorial Bar. I've painstakingly amassed over 4000 courses in the last four years! And out of those 4000, I've only paid for 4 of these courses:
<div style="text-align: center;"><img src="https://i.imgur.com/p79IcDJ.png" width= 50%; height= 50%; /></div>

So, a mere **0.001%** of courses are **actually paid** in my collection! Thankfully, you can get more than what I gathered in 4 years, in a matter of weeks! 🙌🏻

### Why did I create this?
It used to be my daily habit to redeem courses and it was an extremely tedious task that took around 15 minutes, for 10 courses. And then I suddenly got the idea to automate it, after I found the automation course, as mentioned above. I bet, it will save your precious time too! :)

### "Udemy has detected that I'm using automation tools to browse the website! What should I do?"
<img src="https://i.imgur.com/pBrFinT.png" />
Relax! This happens when you run the script several times in a short interval of time. Solve the captcha, close the browser and the webdriver, and simply re-run the bot. Easy peasy lemon squeezy! 🍋🙃

---

***Disclaimer & WARNINGS:***</br>
***1. Make sure you have cleared any saved Debit/Credit Card info from your Browser & your Udemy account before using the script!***</br>
***2. Also, the script has only been tested on the Microsoft Edge Browser but I'm pretty sure it will work on any browser that provides a webdriver for automation.***</br>
***3. Make sure web-scraping is legal in your region and I'm not responsible for any kind of issue caused by the code.***</br>
***4. This is NOT a hacking script, i.e., it can't enroll you for a specific course! Instead it finds courses that provide coupon links to make the transaction free and then LEGALLY enroll you to the course!***</br>
