**SCRIPT 1**

For this project, the purpose was to work with a script that scrapes the 5-day weather forecast from the National Weather Service website. The script extracts information from multiple elements listed under the same class name using the BeautifulSoup library. I downloaded the NWS_WeatherForecast.py file and opened it in Google Collab. I then edited the NWS_WeatherForecast.py script to take latitude and longitude values as inputs in decimal degrees and Convert the latitude and longitude values to strings to generate the URL for Chicago, IL. I passed this URL as an argument in the get() request. The returned forecast information did not preserve its spacing during the scraping process. Hence, I used the replace() and regex() function to fix any spacing issues with the output. I then converted the final output to uppercase using .upper() method.

I referenced the section “string manipulation techniques” under the lab assignment on Clark Moodle titled “Lab 4” from the Python Programming class to create a multiline string with the replace() method. To create spaces between intended words using the regex() tool, I referenced geeksforgeeks.com under the link: https://www.geeksforgeeks.org/python-add-space-between-numbers-and-alphabets-in-string/. To uppercase the final output using the .upper() method, I referenced geeksforgeeks.com under the link: https://www.geeksforgeeks.org/python-string-upper/. I was able to delve deeper into this tools and methods used in Python with this project that I can definitely see coming in handy in my future coding experience. 

The script functioned just about alright. A major error that I was encountering while creating the final output was that I was unable to use the split() method to remove the unwanted symbols from the final output. In future, I would like to fix this error so the final output comes out much cleaner than what I had originally intended. I would also like to condense the entire script for a rather efficient and compact coding experience. 


**SCRIPT 2**

For this project, I tried to combine two labs that were taught in the Python Programming class to create a script. I was taught in class to scrape an image from Wikipedia, but I Web scraped an image from another website for this project. I was taught to use the basic elements of creating a chat bot, but for this project I created a branched chat bot script that makes use of information from the web scraped image.

In this script, an online image from medpagetoday.com that contains information about the 3 Covid-19 vaccines currently available in the U.S. is web scraped to be downloaded locally. Then, a chat bot function called “Covid-19 vaccine FAQs” will be created that will use the information from the downloaded image to provide vaccine related information to its users. This chatbot function takes a Covid-19 vaccine company name as an input (Pfizer, Moderna, Janssen), followed by the subcategories as an input (Vaccine name, MOA, Dosing schedule, Efficacy), to produce an output containing specific information within the subcategories of each individual Covid-19 vaccine company.

The resources I used to create this script were the link to the webpage from where the image was scraped (url: https://www.medpagetoday.com/specialreports/exclusives/91489). To web scrape the image, I referenced the section “Scraping images” under the tutorial assignment on Clark Moodle titled “Web-scraping in Depth” from the Python Programming class.  To create the chat bot function, I referenced the section “Create your first chat bot” under the lab assignment on Clark Moodle titled “Data classification and chat bots” from the Python Programming class.  

In the future, I would like to incorporate a dictionary within this project with multiple lists containing ‘key’: values features and do calculations with them, such as web scraping live text information about the doses available of a certain Covid-19 vaccine company at a vaccination site, and the number of people registered to get the vaccine at the site offering the Covid-19 vaccine of that company, in order to calculate how many doses of a certain Covid-19 vaccine company are still available at the particular vaccination site for people to be registered. I could code this information in the chat bot for users to make a better decision about the vaccine they would like to receive. I would also like to web scrape some text information in future regarding qualitative data about the Covid-19 vaccines.

A major error that I was encountering while creating the chat bot was that the input letters are Case sensitive. I figured it out after a couple failed attempts in trying to receive an output. I would like to fix this error while creating chat bots in future. 
