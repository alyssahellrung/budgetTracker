# Budget Tracker -- Homework 18

## Description  
A simple budgeting application with offline capability. 

## Table of Contents

* [Technologies Used](#technologies-used)

* [How to Use](#how-to-use)

* [How I Made This](#how-i-made-this)

* [Deployed Application](#application-deployed-with-heroku)

* [GitHub Repo](#link-to-github-repo)

* [Future Development Ideas](#future-development-ideas)  

## Technologies Used  
Built in Visual Studio with          
HTML       
CSS  
Bootstrap        
Javascript        
Node.js   
Morgan   
Express   
MongoDB  
Mongoose   
IndexedDB  
Manifest  
Service Worker  
Cache API       

## How to Use    
Navigate to https://salty-mountain-08084.herokuapp.com/. You will see a page all ready for you to enter transactions. Just type the name of the transaction and the amount of the transaction in the corresponding fields. Then click either the "Add Funds" or "Subtract Funds" button depending on which transaction you are making. Once you click the button, the grand total at the top of the page will change to reflect your new balance, the transaction will appear in the list of transactions, and you will see the graphical representation of your transactions change at the bottom of the page. Disconnected from wifi? No problem! The app will work offline as well!  
   
![image](https://media.giphy.com/media/kGuERMToh8otgUJeXF/giphy.gif)  

## How I Made This      
I was given a functioning application and asked to make it work offline. Because I was turning this into a progressive web app (PWA), I added a manifest. I also added a db.js file to set up IndexedDB functionality. IndexedDB will now store transactions when the user is offline and then push them to the Mongo database the next time the user is online. I used service workers with a cache API to make this work. I then adjusted index.html and index.js to link everything together and make it fully functional, online and off!

## Application Deployed With Heroku:
https://salty-mountain-08084.herokuapp.com/

## Link to GitHub Repo    
https://github.com/alyssahellrung/budgetTracker 

## Future Development Ideas
--Better styling  
--A delete button to delete old or incorrect entries  
--A way to keep track of spending over time in specific increments: by day, month, week, and/or year  