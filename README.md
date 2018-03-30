# How to run this Ruby on Rails application?
1. Download Docker
2. Boot the application
    - Terminal Command: `docker-compose up`
3. Create the database
    - Terminal Command:  `docker-compose run web rake db:create`
4. Boot the application again
    - Reminder: Remember to delete the file `./tmp/pids/server.pid`
