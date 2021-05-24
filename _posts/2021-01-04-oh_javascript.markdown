---
layout: post
title:      "Oh JavaScript!"
date:       2021-01-04 23:19:12 -0500
permalink:  oh_javascript
---


Oh JavaScript!


It's a pandemic, schools are remote, parents are teachers and I needed help! 

So I came up with the idea of builiding an application that would allow kids who are fully remote to get some supplemental learning done. An After School web app seemed like a valuable tool and I was curious about building one.

I built this project in two parts using a back end Rails API database side and the front end JavaScript side. My backend was built first to provide functionality and seed info that were required for the frontend.

Enter Rails Scaffold generator! Finally getting to give this generator a whirl and it did not disappoint. Outside of manually entering my seed data and making a couple tweaks here and there, use of this generator made the database generation almost automatic. 

Ensuring that my CORS gem was bundled and tables migrated, moving through the backend was somewhat effortless. 

On the front-end was a slightly different story!

My first snag was building a DOM I could manipulate which admittedly took a few tries. My inital attempt was overdoing it to the point that I was falling victim to hard-coding. But to show the real functionality of DOM manipulation using JavaScript meant less hard-code and more `fetch`ing.

`fetch`ing in this JavaScript project was the process of using the API backend URL, assigning its endpoint and retrieving information in the form of hashes which could then be manipulated to suit the project's functionality requirements. 

A standard `fetch` request is made up of the inital call to the database URL and corresponding endpoint, which, using a `.then` method, returns an inital hash of information in the form of a `promise`. The standard procedure for this initial `promise` is to convert it to JSON before attempting to manipulate it. Once converted to JSON it returns yet another promise after the `.then` method is called again which we can use to achieve some desired functionality. 

`fetch`ing turned out to be a great tool during this build. In addition to its flexibility, it made for a very dynamically created site which could easily be updated if I ever decided to make changes, avoiding all the manual labor that comes with hard-coding.

Many class methods and functions later, my application is fully functional. I will explore building additional features for this application but this introduction to JavaScript is already showing itself to be the most valuable coding language I have learned yet!

