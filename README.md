# II_TECHTASK

This repository contains a sample techincal task of Interactive Investor Automation QA role using webdriverIO. It uses the chromedriver NPM package that wraps the ChromeDriver for you. This service does not require a Selenium server, but uses ChromeDriver to communicate with the browser directly.

Based on the requirement, I have used only one Page Object class to maintain all the webelement locators and Helper methods. We can enhance the framework further when the requirement gets bigger using some good practices of the automation but right now I tried to make the code look simple and clear.

#**Quick Start:**

Clone the git repo - **git clone https://github.com/aalle9875/II-test.git**

Install the dependencies and node modules - **npm install**

Runner - **./node_modules/.bin/wdio wdio.conf.js**
