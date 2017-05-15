# Udacity-Nanodegree-Project-2

<b> Author: </b> Natalie Butler

<b> Project: </b> re-create a responsive portfolio based on a design mock provided

<h1> About </h1>

This program creates a 'Portfolio' of my undertakings as a part of the Udacity Nanodegree. Users can click on the photo image to get more information about these projects through Bootstrap's Modal. Projects that have not yet been completed are 'Coming Soon'. Users can also click on the Udacity github link to take them to the relevant assignment, but again note these links will be updated as more projects are completed.


<h1> CONCEPT TO IMPLEMENTATION </h1>

The following project guidelines were provided:
- download the design mock file and review it
- identify various boxes you will need to build in order to recreate this design
- write your own HTML and CSS files, and iterate until your work is representative of the design mockup
- personalise your portfolio with custom colors, additional content and your own images
- validate work against W3C's Validators

<h1> HOW THE PROGRAM WORKS </h1>

The page displays a 'portfolio' style of the projects via Bootstrap and personalised HTML and CSS files. 

The mock-up webpage has been recreated by making use of columns. For example, col-md-1 has a width of 8.33%, col-md-2 has a width of 16.66% while col-md-3 has a width of 25% and so on, up to col-md-12 with a width of 100% of the viewport. The image below details columns within style.css

![columns](https://cloud.githubusercontent.com/assets/25575132/26055273/8470f6c0-39b3-11e7-90a7-eac288102e18.png)

A number of media queries have been created which display content at different viewports. These breakpoints were selected by viewing the webpage and from there deciding where they are necessary for both smaller and larger viewport widths. The image below details media queries within style.css

![mediaqueries](https://cloud.githubusercontent.com/assets/25575132/26055268/7a4fa970-39b3-11e7-850e-0496d0f8a8f8.png)

Modals have also been implemented, which are a part of Bootstrap's responsive design. These modals provide users with more information about each project. The image below details one of the modals, for the Item Catalog Project, which is a part of Bootstrap functionality. 

![modal](https://cloud.githubusercontent.com/assets/25575132/26055243/4fb17aa4-39b3-11e7-9de0-14dc4fea9700.png)


<h1> SETUP </h1>

Download the files in this git repository, and place them in a directory folder with the same strucuture as follows:


<h1> RUNNING THE PROGRAM </h1>

Once you have downloaded the files, use the index.html file to run the program. This is done in IDLE by clicking Run in the menu bar, followed by Run Module. This will generate the Portfolio page.
