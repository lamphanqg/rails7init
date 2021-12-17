# Boilerplate for Rails 7

## Stack
* Rails 7
* MySQL 8.0.25
* Rspec
* Standardrb
* dotenv
* letter_opener_web

## How to use
* Clone or download this repository
* Replace `rails7init` with your app name in every files
* Run `docker-compose build`
* Run `docker-compose run --rm runner bundle install`
* Run `docker-compose run --rm runner bundle exec rails db:create`
* Run `docker-compose run --rm --service-ports rails` to start server
