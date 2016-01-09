# What is Angular and why does it exist?

## Overview

In this lesson we're going to be looking into AngularJS (commonly referred to as just "Angular"), an open-source framework that was released in 2009. It is currently being mainly maintained by Google as well as a massive community of developers.

It aims to solve the problems faced when creating single page applications, implementing a MVVM pattern to separate presentation and business logic.

## Objectives

- Describe what Angular's role in the web platform is
- Describe the issues Angular looks to solve

## Frontend Frameworks

Ever wondered how Facebook can have a different timeline for millions of users? How Twitter can display tweets for 300 million people? That's where frontend frameworks come in. 

Frontend frameworks have grown massively in the last 3 years. They help developers structure their applications and create interactive, super quick applications.

### Life before frameworks

Before we had the pleasure of using frontend frameworks, code would be written very procedurally. JavaScript code would become unwieldy as there was no easy way to structure code for each page that the client would see.
  
You'd be limited to just simple JavaScript interactions, such as submitting a form via AJAX. Anything more wouldn't have been scalable, resulting in a hard to debug/manage codebase. 

### Frontend frameworks save the day

Imagine being able to write complex JavaScript applications, having a framework deal with scaling your code, splitting it out into logical chunks and not have to worry about one part breaking another.. Sounds like a dream! Oh wait.. Angular does that for us!

## Traditional Rendering

Before mainstream JavaScript usage, the server would do everything for us. When we'd go to a website, everything we needed on that page would be given to us there and then. For instance, if you go to http://wikipedia.org, the server loads the content and sends it back to us.

The problem with this is that data displayed on the page could only be updated when the user refreshes. This also meant no smooth transitions between pages (every page the user navigated to would be reloaded in the web browser).

We'd also then have all of our frontend logic mixed in with the backend logic - resulting in a horrible mess if not structured properly!

## The role of Angular

Angular brings power to the frontend, handling routing as well as all of our pretty, interactive views. This allows frontend developers and backend developers to focus on their areas - there's no need to mix code between the two.

Angular promotes correct and consistent code architecture, helping to structure our applications and removing spaghetti code.

Angular allows us to write powerful applications without much training. They attach onto HTML's disadvantage - that it is only good for static web pages (ones that don't update). 

How do they do this? By implementing more features into HTML! With the use of Angular, we can have dynamic lists repeating, elements hidden and shown dynamically and much much more - just by writing our HTML (with a few, simple modifications that we will come onto soon!).

Before Angular, we'd generally use jQuery to make all of our AJAX requests, as it gave us a cross-browser implementation (there used to be no standard way of making AJAX requests!). This was great, but you were left to yourself to do stuff (like update your view, or display error messages etc) after the request had been completed.

However, with Angular, we're given the tools to easily make AJAX requests and keep our pages updating in real-time without having to refresh. Awesome!