---
layout: post
title:      "Building an MVC Sinatra Application"
date:       2020-02-16 22:57:42 -0500
permalink:  building_an_mvc_sinatra_application
---


Our cohort has now reached the second project in our course - building a basic Sinatra Web Application. For me, this project was the first step to really getting a feel for how a developer works by way of planning and building an application.

Sinatra is a Domain Specific Language (DSL) web framework written in Ruby which can be used to create web applications. In this case, the requirement was to build an MVC application in Sinatra. 

MVC stands for Models, Views and Controllers and each component works together to create a user experience that satifies both the front end expectations, as well as the back end intricacies.

**Models**
This component is responsible for handling the data and logic of the application. 

**Views**
This component is responsible for rendering anything the user sees when interacting with your application. Including text, pictures and functionality, it also is responsible for styling and graphics. 

**Controllers**
This component works as the go between for the two previous components. It accepts input and converts it to commands for the models and views.

Using the Corneal gem in tandem with the Sinatra famework created much of the template for this project. It set up all of the files as well as the structure. The contents of these files were updated to essentially build the project. 

Building out the MVC is a huge part of what is needed to set up the functionality of a Sinatra project. Working mainly in the app folder where the models, views and controllers folders are located, the body of the project is created, the folders linking to each other by way of inheritances, embedded ruby and HTML. 

The importance of building out the MVC is not meant to understate the importance of other folders that make up the structure of the program! Your gemfile plays a significant role as it loads all the gems required to execute your program. The config folder contains an environment file which, amongst other things, establishes the connection to Active Record which is responsible for storing objects in relational databases. Each individual file and folder plays its role in the entire application coming together.

The Sinatra framework running on top of Rack allows for the creation of both simple and dynamic Ruby web applications. At its core it is essentially sending and receiving requests to and from the server which are written inside of the controller function. The controller function, with a main Application Controller from which any sub-controllers inherit, carries the bulk of functions and code responsible for the application. 

Building my project was definitely a learning experience. The Sinatra framework is a stepping stone to Rails which we enter into next and understanding the fundamentals will definitely smoothen the transition by just that much.










