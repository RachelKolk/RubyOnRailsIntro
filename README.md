# RubyOnRailsIntro

Rails App Structure

type 
    rails new app_name 
in the terminal to begin a new project

Rails follows an MVC structure
    -Model, View, Controller
    - the controller reaches out to the Model and the Model lets the controller how the view should be rendered
    - the model has contact to the database


App contains the assets -
 images, stylesheets, javascript, helpers for views, models

Config -


to start the local server type 
    rails server 
into the terminal


Model, View, Controller and Rails App Structure - Text references
To create a new directory called rails_projects:

mkdir rails_projects

To start a new rails application called test_app:

rails new test_app

MVC - Model, View, Controller

General flow of Rails application:

-> Request made at browser

-> Request received at router of rails application

-> Request routed to appropriate controller

-> Controller either renders a view template or communicates with model

-> Model communicates with database

-> Model sends back information to controller

-> Controller renders view
 