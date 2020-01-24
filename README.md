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


[Resetting the Database](https://edgeguides.rubyonrails.org/active_record_migrations.html)
#rails db:reset = rails db:drop & rails db:setup

[Loading Seed(create admin user) and Sample Data](https://stackoverflow.com/questions/36641372/rails-how-to-get-sample-data-with-spree-commerce-sandbox)
1. bundle exec rake db:seed
2. bundle exec rake spree_sample:load