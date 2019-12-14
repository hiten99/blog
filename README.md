This is a very basic Blog application with CRUD functionality.
Each Post consists of title and content.
You can create, edit, update and delete posts.


Prerequisites:
- Ruby version 2.3.3
- Rails version 5.1

Blog for Ruby on Rails application

Steps to install the application:
1. Download and unzip or clone the repository.
2. Open command prompt in the code directory 
Run following commands:
1. bundle install
2. rails db:migrate
3. rails db:seed
4. rails db:migrate RAILS_ENV=test
5. rails test
6. rails s
use the browser to visit the website and try out features: http://localhost:3000/posts/