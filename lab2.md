# Lab Report 2 - Servers and Bugs

## Part 1
For my web server ```StringServer```, this is my code:

![Image](Screen Shot 2023-04-22 at 11.50.02 PM.png)

When I put the request ```/add-message?s=Hello```, the page shows this:

![Image](Screen Shot 2023-04-22 at 9.39.49 PM.png)

The ```public String handleRequest(URI url)``` method is called when I put the request ```/add-message?s=Hello```. The relevant argument to the ```handleRequest``` method is ```URI url```. On line 5, I initialized a variable called ```string``` which has type ```String``` and the value ```""```. Without this initialization, the page shows "404 Not Found!". The value of ```string``` changes when ```/add-message?s=Hello``` is requested. It changes from "" to the words that are after the equal sign in the request. 

When I put the request ```/add-message?s=How are you```, the page updates to this:

![Image](Screen Shot 2023-04-22 at 9.45.48 PM.png)

## Part 2

## Part 3
