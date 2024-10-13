# imgdownloader
README
Project: Google Image Downloader and Email Sender
Overview
This project is a Flask web application that allows users to search for images using a custom Google Search API, download a specified number of images, and receive them as a ZIP file via email. It utilizes the Google Custom Search API to fetch images based on a keyword and sends the downloaded images to the user through email.

# Features:
Search for images using a keyword via the Google Custom Search API.
Download a specified number of images from the search results.
Compress the images into a ZIP file.
Send the ZIP file to the user's email using Gmail's SMTP server.
# Prerequisites:
Python 3.x
API key and search engine ID for Google Custom Search.
Gmail credentials to send emails.
Required Python libraries:
flask
flask_cors
flask_mail
google-api-python-client
requests
shutil
zipfile
io
![image](https://github.com/user-attachments/assets/d06824af-9a26-43c6-bd4a-8ff59e730e41)
