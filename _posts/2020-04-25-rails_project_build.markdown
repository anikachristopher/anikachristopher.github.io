---
layout: post
title:      "Rails Project Build "
date:       2020-04-25 07:54:41 +0000
permalink:  rails_project_build
---


Fresh off the heels of learning the Sinatra framework, I was introduced to Rails as a higher level, increased functionality framework that sought to accomplish not just what its predecessor did but with added functionality and at a more evolved and efficient level.

The excitement of working with generators first stirred my interest. The thought of no longer having to manually build models, controllers and migrations by hand and instead switch to a more automated method was enough to make me a believer.

For my Spa app, I generated a Clients Controller, the main function of which was to handle all client related functionality.  The quick command to do this was:

```
rails generate controller clients first_name last_name email phone
```

From this very simple instruction, I received a controller folder set up with inheritance from Application Controller:
```
class ClientsController < ApplicationController

    def index
    end 
```

It also developed a client route and views directory. From there, all that was left to do was populate the folders and files within the directory to build on the app's functionality.

In addition to the controller, using the  `rails generate ...`  command creates models, migrations, resources and scaffolds, the last of which we we prohibited from using in this project. 

Although the convenience aspect of Rails' automation is handy, I still prefer a bit of manual control. Not using the scaffold generator was no issue since using even the resource generator was a bit much for me this time around. I used it on my first attempt at this project and ended up having to scrap and start over because there was so much going on and I couldn't fully grasp how things were related.

Working with the Omniauth gem on this project was also a new experience. In tandem with the Dotenv-rails gem,  its job in a nutshell is to assist in making your app more accessible to the user by providing what is essentially an easy validation process. Once connected, a user can access your app with credentials from another site like Facebook, Google, Twitter and GitHub. This does a couple outstanding things. 

Firstly, it takes that total responsiblity of validating user credentials away from you as the app's creator and channels it instead to an entity much more equipped to handle it. With their substantial budget allowances and all around manpower, tech juggernauts like the previously named have much more sophisticated processes to provide adequate user authentication.

Another, and for me very important, thing it does is it makes your app more accessible and user friendly for those who may not want to create new accounts for every site they visit. It creates a one stop shop for access for someone who most likely has an account with at least one of the bigger entities and would prefer the option of using already established log in credentials for access.

This project was a welcomed learning experience and the Rails framework is a great tool. Looking forward to learning how JavaScript will enhance its efficiency.

