# Audience_Generator
## Description
Audience_Generator is a web application designed to create targeted audience profiles based on user-entered keywords. The application retrieves data from social media platforms using ethical practices and APIs, analyzes the sentiment using a RoBERTa-based transformer model, and selects users with positive sentiments to form a curated audience. This tool is ideal for marketers, researchers, and social media managers looking to engage with a positively inclined audience.

![Screenshot of Audience_Generator](screenshots/home.jpeg)


- Application once run will search users who have posted anything positive related to the entered search term/topic
* For Reddit and Twitter it will search the best posts related to the topic
* For youtube it will search the video related to the topic and return comments in that video  

- Instructions to run the app:
run the 'main.py' file

- make sure all the libraries are imported from the installed_packages.txt to avoid any errors
- run the main.py file which should launch the flask website

Note: Below are the details used for respective platforms while making API calls for data extraction these can be updated in their respective python files updated_app>routes>python files


- Reddit: The credential for reddit can be created from personal reddit account in the PRAW API
Create personal ID and secret key for reddit

- Twitter: As twitter developer account is paid use it to create a bearer token

BEARER_TOKEN='XXXX'

- YouTube: The credential for Youtube can be created from personal youtube account in the Youtube data API

All credientials which are generated by the personal user account

