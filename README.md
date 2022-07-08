# README

This README would normally document whatever steps are necessary to get the
application up and running.

To setup project locally, follow below instructions.
Project Configuration : 

Have ruby version ruby-3.0.0 installed as mentioned in Gemfile.
and Rails version-6.1.4 as mentioned in Gemfile.

Install necessary dependencies.

# install dependencies mentioned in Gemfile
$ bundle install

# verification of already installed files in node_modules
$ yarn install --check-files

Database Setup
Create and Initialize database.

# migration of database
$ rails db:migrate

Starting the server
To start the server on localhost run the command below. The server will start on default port 3000.

$ rails s

