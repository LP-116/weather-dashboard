# Web Design Challenge
## Web Visualization Dashboard (Latitude)
## To view the visualisation dashboard click [here](https://lp-116.github.io/web-design-challenge/index.html)

---
### Task

The purpose of this task was to use HTML and CSS to create a dashboard showing an analysis completed on the weather data of 500+ cities.

The website needed to contain 7 pages:
* A landing page which gives an explanation of the project and links to each visualisation. (Note: the landing page is also known as the index page)
* 4 x visualisation pages that displays the graph selected with a short paragraph of findings. Each page needs to contain links to the other visualisations.
* A comparison page that displays all graphs on the same page.
* A data page that contains a table displaying the data used to create the visualisations.

Each page needs to have a navigation bar that consists of a drop down menu that contains links to each visulaisation, a clickable link to the comparison page and data page, and a clickable button to the home summary page. 

Each page needs to be responsive meaning that it needs to be able to be viewed on smaller screens.


---
### Method

To complete this task I started by choosing a theme from Bootswatch to make the site unique and challenge myself to get creative. I ended up choosing the "Superhero" theme as the colors went well with what was used in the visualisations.

Once the theme was downloaded, it was saved as a css file and added into the github project file. This css file contains the default colors of the them and is used along with another style.css file that I have personalised.

The first step was creating the nav bar that will be used on all 7 web pages.

The base nav bar code was taken from Bootstrap and then modified to include the required text, link references and positioning.

Next a grid was created (using Bootstrap base code) to display a summary picture in one half and links to the visualisations in the other. 
I set the columns to "lg" as I found this worked best for the theme and viewing in a smaller screen.

The visualisation pages were created next. I opted to use 11 of the 12 grid spaces as I found using all 12 not as visually appealing.
Another grid was used, 1 taking up 8 spaces and the other taking up 3 spaces.
The big grid space contained a big image of the graph being reviewed and a short paragraph detailing findings.

The smaller grid section on the visualisation page contained links to the other visualisations.
I also added in a "Next" button for an alternate easy navigation through the graph images.

The comparison page was then created using a grid of 2 x 2 (each grid taking up 6 spaces each).
Clicking on each graph links back to the visualisation summary.

Lastly, the data graph was created. Pandas was used to convert the csv file to a data html file. This was then used as a basis for the data page.
The navbar was added to the html code and a table inside a grid was applied to the code.

Once all pages were created, media queries were applied to ensure all pages were responsive when in a smaller window size and on a mobile device.

---
### Results

The webpage has been published in this github respository.
To view the visualisation dashboard click [here](https://lp-116.github.io/web-design-challenge/index.html)

The site can also be viewed on a mobile device:
![Screenshot_20210725-161902_Samsung Internet](https://user-images.githubusercontent.com/82348616/126890244-d50daa3c-adc8-4372-afeb-4801ea2d929d.jpg)
![Screenshot_20210725-161909_Samsung Internet](https://user-images.githubusercontent.com/82348616/126890248-bfacb4aa-114c-4b29-9b12-959bafb2ac90.jpg)
![Screenshot_20210725-161923_Samsung Internet](https://user-images.githubusercontent.com/82348616/126890251-118af389-4bff-415e-b739-e3dd1f14d2f2.jpg)
![Screenshot_20210725-161931_Samsung Internet](https://user-images.githubusercontent.com/82348616/126890252-61de419f-31e5-4fc9-b48a-0d5ad7c3c54f.jpg)


---
### Files

This repository contains the below files:
* An Assets folder - contains all the images used in the dashboard.
* A CSS_files folder - contains the CSS files.
* A Resources folder - contains the cities.csv file.
* A Visualisations folder - contains the visualisation html files.
* A data.html file - the data page.
* A index.html file - the index page (or landing page).
* A table-to-html.ipynb file - the python file containing the code used to convert the csv file to html.
* A table.html file - the html file created from the python code (note: this is note a page in the dashboard, the table code was used in the data.html file).


