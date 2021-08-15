# Amazon Price Tracker [⏩](https://github.com/KrShivanshu/Amazon-Price-Tacker)

by Kumar Shivanshu 
[Github](https://github.com/KrShivanshu/)

### It is an automated web scraper which can be used track few top products on Amazon based on given arguments and store its link, title, seller and price in json format.
---
### It receives arguments like:
1. Product Name
2. Min Price
3. Max Price

## Prerequisites 
1. Python version 3.0 or above installed in system.
2. Terminal or command prompt 
3. Chrome browser installed 

## Steps to run the application
1. Download the project
2. Extract the zip file of the project 
3. Find your chrome version
    - Open Chrome -> Settings -> About -> Version
4. Download chrome driver same as your chrome browser version
    - [Download Chrome Driver](https://chromedriver.chromium.org/)
    - Extract and save the .exe file in project root folder
    - Driver name should be "chromedriver.exe"
5. Open terminal and browse it to project root folder
6. Type 
    - > python simple_tracker.py
    -  Press "Enter"
7. Project will run from here automatically and will generate the report in reports folder

Note : You can change the product name, min price and max price in amazon_config.py file based on your requirement.

## Future Scope
1. Can use flask to run it from webpage.
2. Report generates can be of more readable form using JSON formatter.

## Projet Working Screen Recording
![Working](https://github.com/KrShivanshu/Amazon-Price-Tacker/blob/master/others/AmazonPriceTrackerWorking.gif)

