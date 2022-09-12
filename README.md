# Mission-to-Mars

## Overview

Robin's web app is looking good and functioning well, but she wants to add more polish to it. She had been admiring images of Mars’s hemispheres online and realized that the site is scraping-friendly. She would like to adjust the current web app to include all four of the hemisphere images. To do this, you’ll use BeautifulSoup and Splinter to scrape full-resolution images of Mars’s hemispheres and the titles of those images, store the scraped data on a Mongo database, use a web application to display the data, and alter the design of the web app to accommodate these images.

### Scrape Full-Resolution Mars Hemisphere Images and Titles
  Using BeautifulSoup and Splinter, I’ll be abale to scrape full-resolution images of Mars’s hemispheres and the titles of those images.
  
  
The code below helps us retrive the proper information/ url's we need to view teh hemisphere. 
Code is written that retrieves the full-resolution image and title for each hemisphere image. 
The full-resolution images of the hemispheres are added to the dictionary. 
The titles for the hemisphere images are added to the dictionary
  
  ![Screen Shot 2022-09-12 at 10 09 44 AM](https://user-images.githubusercontent.com/102995385/189735859-1c61af24-dea9-4d99-85b4-5e3ba9fb674c.png)

The following gives us the output we are looking for. With the following information we will be bale to scrape date and presnt the date to Robin's fellows. 
The list contains the dictionary of the full-resolution image URL string and title for each hemisphere image.

![Screen Shot 2022-09-12 at 10 08 23 AM](https://user-images.githubusercontent.com/102995385/189736128-a0201f22-3cf7-46b7-8200-1da31a8b4a7f.png)


  
### Update the Web App with Mars Hemisphere Images and Titles
Using the Python and HTML I’ll b able add the code created above from my scraping.py file, update my Mongo database, and modify my index.html file so the webpage contains all the information collected as well as the full-resolution image and title for each hemisphere image.

####    Execuation:


After the scraping has been completed, the web app contains all the information and the full-resolution images and titles for the four hemisphere images.


### Deliverable 3: Add Bootstrap 3 Components
