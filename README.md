# Backbone.js

##Introduction
Backbone.js is a lightweight Javascript front-end library. Backbone was created in 2010 by Jeremy Ashkenas, who also created CoffeeScript and Underscorejs. In a Javascript-heavy application, Backbone solves the problem of having a web of jQuery selectors and callbacks, and provides a streamlined way to keep data in sync. 


Backbone has one hard dependency, which is Underscore.js, a Javascript utility/helper library. jQuery is needed for full use of the library.  

##Getting started
[Backbone.js for Absolute Beginners](http://adrianmejia.com/blog/2012/09/11/backbone-dot-js-for-absolute-beginners-getting-started/) - A detailed, four-part tutorial to create a todo app.

##Backbone as compared alternative to Rails MVC

* Model - When an attribute is changed, an event is triggered, and the view is automatically updated. Similar to a rails model without class methods.
* Collection - A group of client-side models.
* View - Displays the model's state, listens for and renders any changes.
* Router - Maps urls to functions; similar to Rails routes.rb and Rails controller.
* Client-side templates - Renders HTML, like Rails .html.erb views.


##Resources
[Tutorials, blog posts and example sites](https://github.com/jashkenas/backbone/wiki/Tutorials%2C-blog-posts-and-example-sites)

[Backbonejs.org](http://backbonejs.org/)

[Annotated source code](http://backbonejs.org/docs/backbone.html)