# What is Angular and why does it exist?

## Overview

AngularJS (commonly referred to as just "Angular") is an open-source framework released in 2009, being mainly maintained by Google as well as a massive community of developers.

It aims to solve the problems faced when creating single page applications, implementing a MVVM pattern to separate presentation and business logic.

## Objectives

- Describe what Angular's role in the web platform is
- Describe the issues Angular looks to solve
- Describe how Angular thinks in terms of Web Components to create encapsulation and reusable components

## Traditional Rendering

Before mainstream JavaScript usage, everything on the client was determined by the server. Routing and views were defined in backend code, meaning view logic was frequently mixed in with business logic, providing the end-user with a poor user experience.

This had its disadvantages, as data displayed on the page could only be updated when the user refreshes. This also meant no smooth transitions between pages.

## The role of Angular

Angular brings power to the frontend, handling routing as well as all view logic. This allows frontend developers and backend developers to focus on their areas - there's no need to mix code between the two.

Implementing MVVM, Angular promotes correct and consistent code architecture, removing any spaghetti mess that could possibly arise from other MVC/MVVM frameworks.

Angular's view logic is all done in the HTML source code - however, HTML is great for static pages but not dynamic. Angular extends the HTML vocabulary to allow for dynamic views to come to life easily.

Along side dynamic views, Angular also allows you to create components (also known as "directives"). This enables you to create encapsulated components that do one thing (and one thing well), and reuse them throughout your whole application, saving development time.

Angular also boasts two-way data-binding. With traditional rendering, the data couldn't be updated without the user refreshing the page. However, with two-way data-binding, our applications can refresh application data in the background, with Angular automatically binding the data (our "model") to our views - keeping them perfectly synchronised. 
