# README

This README would normally document whatever steps are necessary to get the
application up and running.

Things you may want to cover:

* Ruby version(2.4.0)

* System dependencies

* Configuration

* Database creation

* Database initialization

* How to run the test suite

* Services (job queues, cache servers, search engines, etc.)

* Deployment instructions

* ...
# hello_app

Ruby on Rails Tutorial 5(Vijay)
==============================
*Install gem without production:
=> bundle install --without production

*The -v flag ensures that the specified version of Rails gets installed
=>gem install rails -v 5.1.2

*New app with rails version
=> rails _5.1.2_ new hello_app

*List all controllers
=> ls app/controllers/*_controller.rb

*One-time global configuration settings.
=> git config --global user.name "Your Name"
=> git config --global user.email your.email@example.com

=> git remote add origin git@github.com:vijayshankar037/hello_app.git

*scaffold
=> rails g scaffold User name:string email:string



*Heroku CLI(Command line interface) Setup
=> gem install heroku
=> heroku --version
=> heroku login
=> heroku keys:add
=> heroku create
=> git push heroku master 
=> heroku open
=> heroku rename developebabu-rails
=> heroku apps:info --app example
=> heroku apps:info --remote production
=> heroku run rails db:migrate

*Remove multiple file from a DIR
=> rm public/{404,500}.html


*GOOD LINK:-
https://www.railstutorial.org/book
https://www.learnenough.com/git-tutorial
