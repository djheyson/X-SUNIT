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

For Using

 $ bundle install
 
 $ rake db:create
 
 # this is for generate triggers. I don't know work with this yet
 -- $ rake db:generate_trigger_migration (You don't need execute this if you don't change triggers)

 $ rake db:migrate
 $ rails s


For Testing

Route Survivor: localhost:3000/api/v1/survivors

Show all survivor order by name here

    GET: localhost:3000/api/v1/survivors

Show survivor by id

    GET: localhost:3000/api/v1/survivors/{id}

Create new register of survivor

    POST: localhost:3000/api/v1/survivors

    {
        "name":"Djheyson Oliveira",
        "age": 23,
        "gender":"Male",
        "latitude": 77.332874,
        "longitude": -29.017317
    }