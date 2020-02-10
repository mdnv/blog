# README

This README would normally document whatever steps are necessary to get the
application up and running.

Things you may want to cover:

* Ruby version

* System dependencies

* Configuration

* Database creation

* Database initialization

* How to run the test suite

* Services (job queues, cache servers, search engines, etc.)

* Deployment instructions

* ...

 1132  rails new blog -T -d postgresql
 1133  cd blog/
 1134  bundle
 1135  rails s
 1136  rails db:setup
 1137  rails s
 1138  rails db:migrate
 1139  rails s
 1140  cd
 1141  rbenv install 2.7.0
 1142  cd blog/
 1143  rails generate controller Welcome index
 1144  subl .
 1145  rails routes
 1146  rails generate controller Articles
 1147  rails generate model Article title:string text:text
 1148  rails db:migrate
 1149  rails generate model Comment commenter:string body:text article:references
 1150  rails db:migrate
 1151  rails generate controller Comments
 1152  history

