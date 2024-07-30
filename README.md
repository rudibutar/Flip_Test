# Flip_Test
Test for Test Engineer FLIP

1. Automation API using Postman
precondition :
To activate api key, need login to website https://openweathermap.org/ using your email

Step to create automation : 
- Create the collection file to collect your api that you wanna create the automation
- Save the api key into your collection variable caused api key is mandatory for authorization key
- Fisrt, need hit endpoint coordinate by location to get lat and lot 
- After get lat and lot from response endpoint get coordinate by location and get air pollution , will save to collection variable
- Save value lat and lot to collection variable for another api can reuse the value in one time
- Every important value you need to save into collection variable so you can verify by actual result and your value in collection variable is same or not

2. Automation UI using Katalon Selenium Katalon for safari browser
I used purely code using selenium java, katalon i sed as a tools caused i think katalon already support forselenium and support for java language. But i'm sorry can't done for this automation caused i already trying all the way for part date picker field Date of Birth
For any field is already can automated, only for Date of Birth i don't know how to select the path caused in safari has shadow path and its hard to explore it and solved it

