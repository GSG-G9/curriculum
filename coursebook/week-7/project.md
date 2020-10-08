## Project

This week's project will involve setting up a database which you connect to via a node.js server. You'll use your data to make a dynamic web app for your front-end.

Some suggested project ideas are below. Feel free to modify according to your interest, provided your idea has similar functionality.


### Requirements

- Simple web app with a node server and a database using express, and postgreSql. 
- Your database comes with a schema, which should be documented in your readme (along with any other architectural decisions)
- Database hosted on Heroku.
- Build script for your database
- Security concerns appropriately considered (you must protect against script injections!)
- make both ```POST```and ```GET``` requests to your server
- Content dynamic, but DOM manipulation kept to a minimum
- Mobile-first design
- Clear user journey (even if you take one of our suggested ideas, document the user journey in your readme)
- test your server routes with supertest
- test your pure functions both server and client side
- set up a test database so that you can test your database queries

**Note**
We don't expect you to authenticate users (i.e. have a login or signup page), or even to simulate this feature. We'll cover how to do that properly in later weeks. Since these ideas were designed with Founders & Coders users in mind, we'll rely on trust instead of authentication :)



### Suggested ideas

#### Founders & Coders book sharing system

As a member of Founders & Coders who has a book I would like to share...
* I can add a book to the database

As a member of Founders & Coders who is interested in borrowing a book...
* I can browse for available books
* I can reserve a book for certain dates
* I can unreserve a book

Suggested additional requirements / stretch goals:
* I can rate the book after I've read it
* Books can simultaneously be reserved by multiple users but for different dates

#### Food / coffee recommendations around Founders & Coders

As a member of or visitor to Founders & Coders...
* I can browse recommended places to buy food / coffee nearby
* I can add a new place
* I can add a rating/review of an existing place

Suggested additional requirements / stretch goals:
* Multiple locations
* Show the location with Google Maps

#### Founders & Coders events calendar

As a member of Founders & Coders who likes going to talks or meetups...
* I can add details of an event I'm interested in attending
* I can browse upcoming events
* I can register my attendance at an event or post a comment

Suggested additional requirements / stretch goals:
* Events can be assigned to different categories
* I can browse past events and write a review
