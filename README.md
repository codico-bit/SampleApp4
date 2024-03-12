# What to do

Pack the rails application in a docker container image.
Launch the application in a docker container. Launch a separate container for the database and ensure that the two containers are able to connect.
The DB port should not be exposed to the host or external network. It must be internal to the docker network only.
Expose the application port to the host machine at port 8080. So you should be able to access the app at “localhost:8080”.

NOTE: You are free to change or edit some of the code in this repository according to convinience. You can change the ruby version in the Gemfile, uncomment any gems or change the version of the gems as long as they are mostly using Ruby 2.7 or close (MAKE SURE YOU ARE NOT USING RUBY 3 and ABOVE) and Rails 6.1 or close (MAKE SURE YOU ARE NOT USING RAILS 7 AND ABOVE)