This is a very basic Blog application with CRUD functionality.


Prerequisites:
- Ruby version 2.3.3
- Rails version 5.1

Blog for Ruby on Rails application

Steps to install the application:
Download and unzip or clone the repository.
open command prompt in the code directory 
Run following commands:
bundle install

rails db:migrate
rails db:seed
rails db:migrate RAILS_ENV=test
rails test

rails s
use the browser to visit the website: http://localhost:3000/posts/