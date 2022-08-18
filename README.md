# UFOs
UFO Sightings with JavaScript
## Overview
The purpose of this analysis is building a table about UFO sightings using data stored in a JavaScript array, create filters to make this table fully dynamic that will react to user input, and then place the table into an HTML file for easy viewing. 
## Resources
Data source: data.js<br/>
Software: VS Code 1.68.1   
## Results
### UFO sightings analysis
1.In "app.js" file: Import the data into a table, filter the table with multiple criteria, create a new function to keep only the results that match the search criteria, and finally build the filtered table. Here are some codes below:<br/>
![code of javascript](https://user-images.githubusercontent.com/107179765/185485547-4d6c9a95-6d7b-4152-9c12-4f229e019307.png)<br/>
2.In "index.html" file: build the navigation bar and the jumbotron, add the article title and paragraph, create the table filters, with the filters in place, we're able to build the HTML table. Finally customize the webpage as we like. Here are some codes below:<br/>
![code of html](https://user-images.githubusercontent.com/107179765/185485581-b230f520-ef39-4a17-ad62-ba675ed6afba.png)<br/>
3.Tie the UFO webpage together with the JavaScript code. The JavaScript table will be referenced within the HTML code, and different HTML components will be referenced within the JavaScript code. <br/>
The webpage will be updated with the search criteria after pressing "Enter" and allow users to filter for multiple criteria at the same time.<br/>
![Screen Shot](https://user-images.githubusercontent.com/107179765/185483238-61fcb66a-e2f4-46f3-83c3-87b7a08747f1.png)
### Walk our client through the process of using the search criteria
The user can re-initialize the page by clicking on the navbar at the top. <br/>
Once opening the website, our client will see the basic navigation bar and title with the picture at the top, as the client scrolls down they will begin to see the table with filters that we have. So far, we have 5 different filters to choose from: the date, city, state, country and shape. Our client can enter information at any of these filters search bar at one time, then the HTML page will show all the UFO sightings for that specific search. <br/>
For example, if our clients want to search the sightings in “ma” state at “1/10/2010”, then they can enter “1/10/2010” in date search bar, and “ma” in state search bar to get the output they want. The filtering process shown as below:
![searching process](https://user-images.githubusercontent.com/107179765/185483308-bf761a2d-ba2f-4234-9625-b70df518b527.png)
## Summary
### Descriptions
We’ve created a HTML page that looks neat and tidy in its form, and provide a more in-depth analysis of UFO sightings by allowing users to filter for multiple criteria at the same time. <br/>
One drawback of this new design is the difficulty for the user to know what parameter to use for the filtering. For example to pick a city, the user would have to go through the table to find a city name desired for the analysis.
### Recommendations
For further development, I think we should: <br/>
1.	Create a drop-down menu including all filter values in place of each input fields. <br/>
2.	Including a button to clear all the filters at once. As we may enter several filters at one time, if we want to change the filters we set before to begin another multiple-criteria-searching, it is better for us to create a button to clear all the filters at once before we have next search.
