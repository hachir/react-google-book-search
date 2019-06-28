Google Books Search


Overview

In this activity, you'll create a new React-based Google Books Search app. This assignment requires you to create React components, work with helper/util functions, and utilize React lifecycle methods to query and display books based on user searches. You'll also use Node, Express and MongoDB so that users can save books to review or purchase later.


Commits

Having an active and healthy commit history on GitHub is important for your future job search. It is also extremely important for making sure your work is saved in your repository. If something breaks, committing often ensures you are able to go back to a working version of your code.



Committing often is a signal to employers that you are actively working on your code and learning.


We use the mantra “commit early and often.”  This means that when you write code that works, add it and commit it!
Numerous commits allow you to see how your app is progressing and give you a point to revert to if anything goes wrong.



Be clear and descriptive in your commit messaging.


When writing a commit message, avoid vague messages like "fixed." Be descriptive so that you and anyone else looking at your repository knows what happened with each commit.


We would like you to have well over 200 commits by graduation, so commit early and often!



Submission on BCS


Please submit both the deployed Heroku link to your homework AND the link to the Github Repository!




This application requires at minimum 2 pages, check out the following mockup images for each page:



Search - User can search for books via the Google Books API and render them here. User has the option to "View" a book, bringing them to the book on Google Books, or "Save" a book, saving it to the Mongo database.

Saved - Renders all books saved to the Mongo database. User has an option to "View" the book, bringing them to the book on Google Books, or "Delete" a book, removing it from the Mongo database.





Start by using the 07-Ins_Mern example as a base for your application.
Add code to connect to a MongoDB database named googlebooks using the mongoose npm package.
Using mongoose, then create a Book schema.
At a minimum, books should have each of the following fields:



title - Title of the book from the Google Books API
authors - The books's author(s) as returned from the Google Books API
description - The book's description as returned from the Google Books API
image - The Book's thumbnail image as returned from the Google Books API
link - The Book's information link as returned from the Google Books API

Creating documents in your books collection similar to the following: