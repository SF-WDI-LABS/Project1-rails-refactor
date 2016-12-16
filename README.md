#![](https://cloud.githubusercontent.com/assets/7833470/10899314/63829980-8188-11e5-8cdd-4ded5bcb6e36.png) Project 1 Ruby-on-Rails refactor


## Overview

You've created a great 'MEN' stack app, now make it an equally awesome Ruby-on-rails web application!

## Objectives
  
- practice rapidly prototyping ideas and existing codebase into ruby-on-rails
- translate existing data structures and database schemas to ActiverRecord migrations
- utilize Ruby-on-rails' stylesheeet organization structure 

## Lab rationale

![](http://i.giphy.com/CXHqvgoR5jerC.gif)

This project is designed to reenforce everything you've learned in Ruby on Rails through the translation of your existing full-stack Project 1 web application.  You will identify the main modules of Model, View, and Controller from your Project 1 and transfer the logic and methodology to a Ruby on Rails app.  

![](http://i.giphy.com/J2bvHfn09n0wE.gif)
You may work with your original partner from Project 1 or individually.  If you used a technology that is only available using `javascript` please see an instructor for further guidance.  We do **not** expect a complete deliverable.  We **do** expect a significant amount of effort and thought to be focused on transation and synthesis of the two languages we have learned.

![](http://i.giphy.com/HwpL9rtN47Kne.gif)

Developers with a broad understanding of different frameworks and environments are able to learn new technologies faster than those who are 'siloed' in one technology.  Your resume will benefit from having a more diverse variety of technologies as well as broadcasting your ability to fit into multiple positions and challenges. This lab aims at boosting your confidence and abilities through a typical task of moving an application from one language and framework to another.

## Getting Started

###Repository creation
1. Create a new repository.  It should have the same name as your Project 1 application only with a `rails_` prefix (i.e. `lingo_jungle` becomes `rails_lingo_jungle`.)
2. Within your new repository, create a new rails app.  You will not need the testing suite.  You will be using `postgres`	as your database.

###Database creation
3. Run `rails db:create` in the Terminal to create your local database.
4. Begin building your database structure **as close to** your original project's schema as possible.
5. Run `rake db:migrate` in the Terminal to run migrations.  Test your code in the `rails console`!
6. You may attempt authorization at this point if you feel comfortable.  You are **not** required to create a secure authorization for this prototype challenge. 

###Routes, Controllers, and View
4. Run `rails s` in the Terminal to start your server.
5. Navigate to `localhost:3000` in the browser - you should see a generic `site#index` page.   
6. Begin generating the same routes you had in your Project 1 in `routes.rb`. Create one route at a time and follow the pattern of `route` => `controller` => `view` to build your app incrementally.
7. There is absolutely **NO** need for style at this point.

###Style implementation
1. Implement your original Project 1 style as much as possible onto your new rails app. 
2. Modals, animations, and such are not necessary.  You may attempt to implement them if you would like.
3. Avoid using ruby gems for bootstrap.  Instead consider downloading the css/js files to your `vendor/assets/` folder provided.
	To include the third party css, include this in your  `application.css` file below other `require` statements:
	
	```css
	 *= require_tree ../../../vendor/assets/stylesheets/.
	```

	To include third party js, include this in your `application.js` file below the other `require` statements: 
	
	```javascript
	//= require_tree ../../../vendor/assets/
	```
	
4.  Now would be a good opportunity to learn a little about Sass and/or Flexbox if you find yourself with more time.  Check out our lessons [here](https://github.com/SF-WDI-33/sass-intro)
## Submission

When you're finished working on the rails app:  

- add a 3-5 sentence reflection on this app to the top of your README.  Focus on your impressions of translating the structures from JS to Ruby and their respective frameworks.  

- push your work to the master branch of your repository  
- add a link to your repo on the "My Work" section of your website  

## Optional feedback
This is a lab. This is not considered a deliverable.  If you would like feedback on your efforts, schedule a 1:1 for the week of 12/19 - 12/22 for a code review.  

![Student receiving feedback](http://i.giphy.com/DpB9NBjny7jF1pd0yt2.gif)

