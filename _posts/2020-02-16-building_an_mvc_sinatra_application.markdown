---
layout: post
title:      "Building an MVC Sinatra Application"
date:       2020-02-16 22:57:42 -0500
permalink:  building_an_mvc_sinatra_application
---


The October 7th 2019 cohort has now reached the second project in our course - building a basic Sinatra Web Application. For me, this project was the first step to really getting a feel for how a developer works by way of planning and building an application.

Sinatra is a Domain Specific Language web framework written in Ruby which can be used to create web applications. In this case, the requirement was to build an MVC application in Sinatra. 

MVC stands for Models, Views and Controllers and each component works together to create a user experience that satifies both the front end expectations, as well as the back end intricacies.

**Models**
This component is responsible for handling the data and logic of the application. Classes built in this component inherit from ActiveRecord::Base. To satisfy the requirements of this project, this component also features a has_many and belongs_to relationship.

**Views**
This component is responsible for rendering anything the user sees when interacting with your application. Including text, pictures and functionality, it also is responsible for styling and graphics. 

**Controllers**
This component works as the go between for the two previous components. It accepts input and converts it to commands for the models and views.



