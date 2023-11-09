# Proposal

## What will (likely) be the title of your project?

Sports Seeker

## In just a sentence or two, summarize your project. (E.g., "A website that lets you buy and sell stocks.")

A website that allows you to input a zipcode and searches for local and public sport centers, arenas, etc. 

## In a paragraph or more, detail your project. What will your software do? What features will it have? How will it be executed?

The software will be able to take an input from user that is any valid zip code. The software will then take the zip code and analyze close sport arenas/recreation centers that are close by. The frontend will be made with html and css. CSS will style the website so it doesn’t look bland and use input boxes to let people type in their zip code. When the person clicks the “Find location” button, there will be an onClick function in javascript in our HTML file that will send an api request to our flask server. Our flask server will be sending a request to Yelp API with “location” as a query parameter. Once it is received successfully, it will reply with location as a json arrays. 
## If planning to combine 1051's final project with another course's final project, with which other course? And which aspect(s) of your proposed project would relate to 1051, and which aspect(s) would relate to the other course?

N/A

## If planning to collaborate with 1 or 2 classmates for the final project, list their names, email addresses, and the names of their assigned TAs below.

Kush Patel, tur46917@temple.edu, Xinwen Zhang

## In the world of software, most everything takes longer to implement than you expect. And so it's not uncommon to accomplish less in a fixed amount of time than you hope.

### In a sentence (or list of features), define a GOOD outcome for your final project. I.e., what WILL you accomplish no matter what?

We will at least have a web application that takes in values.

### In a sentence (or list of features), define a BETTER outcome for your final project. I.e., what do you THINK you can accomplish before the final project's deadline?

The website will be able to send queries to the backend.

### In a sentence (or list of features), define a BEST outcome for your final project. I.e., what do you HOPE to accomplish before the final project's deadline?

The website will be able to redirect the user to the information that is connected with the respective sports center or arena that they are interested in and send back actual information from Yelp API. 

## In a paragraph or more, outline your next steps. What new skills will you need to acquire? What topics will you need to research? If working with one of two classmates, who will do what?

