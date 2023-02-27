# UFOs
## Overview of Project 
In this project, we are using JS, CSS and html to search a data set and display the results. There are several search fields such as date of the sighting, place where the UFOs where sighted (city, state, country) and the shape of the reported UFOs. 
## Results
The current web app allows the user to search through relatively a small data set and observe the summary on the app. For instance, if the user is interested in listing all the sightings on 1/4/2010, then they can input the date in the date field (as shown in the illustration bellow with a red arrow). Upon making the change, the list will appear on the right side of the screen as illustrated in the figure. 

![fig1](/UFOs/pics/pic1_date.png?raw=true "searching for dates")

The search can easily be expanded to other fields. For instance, if one is interested in listing the sightings on the same date in the city of cidar rapids, then they simply add cider rapids to the field labeled ”city”. Upon making the change the list of all the sightings on 1/4/2010 in cider rapids will be shown, as seen in the following figure with cyan arrows.
![fig2](/UFOs/pics/pic2_date_city.png?raw=true "searching for dates and city")

##Summary
This simple web app allows the user to use multiple fields to look for data. However, the way the app is written as of now, an independent search is done every time a change is made. While this works fine for a small data set such as the one in this exercise, repeating the search could be quite time consuming for larger sets. Therefore, one can improve the existing code to wait for all inputs for all fields and then search the set. 
In addition, the current code only allows for one entry for each filed. Expanding to multiple entries can be of some use for.
