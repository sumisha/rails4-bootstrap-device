Requirements
------------
	Ruby 2.0
	Rails 4.0.0
	Mysql

Installing the appplication
===========================

The application has .rvmrc file. It will automatically create the gemset if it does
not exist.

Now, clone the repository:

    git clone git@github.com:sumisha/rails4-bootstrap-device.git 

Then go to the applications directory and bundle it:

    bundle install

Database setup
=====================

Run the following command to create the database.

    rake db:setup

Running the application
=======================

    rails server
