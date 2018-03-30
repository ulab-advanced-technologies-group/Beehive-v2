# Beehive Version 2.0

A refurbished version of the original [Beehive](https://github.com/ucberkeley/Beehive) that is written in Rails 5!

## How to run this Ruby on Rails application?
1. Download Docker
2. Boot the application
    - Terminal Command: `docker-compose up`
3. Create the database
    - In another terminal, run:  `docker-compose run web rake db:create`
4. Boot the application again
    - Same procedure as step 2
    - [Reminder](https://docs.docker.com/compose/rails/): Delete the file `tmp/pids/server.pid` if you stop the application with `Ctrl-C` in the same shell in which you executed the `docker-compose up`
    - To stop the application, run [docker-compose down](https://docs.docker.com/compose/reference/down/) in your project directory (preferably in a different shell than the one in which you executed the `docker-compose up`)
