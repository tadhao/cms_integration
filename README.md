# README

# Instructions to install Camaleon CMS in Rails 6

* Add "gem ‘camaleon_cms’" in Gemfile

* Add "gem ‘draper’,’~>3’" in Gemfile

* Run "bundle install" on terminal

* Run "rails generate camaleon_cms:install" on terminal

* Run "rake camaleon_cms:generate_migrations" on terminal

* Run "rake db:migrate" on terminal 

* Add "//= link camaleon_cms/admin/admin-basic-manifest.css" in /PROJECT_NAME/app/assets/config/manifest.js at end of the page

* Run "rails s" on terminal

* Select any theme, note down the admin credentials and enjoy!


# Short Note :

* In case you forget to note down the admin credentials then, run "rake db:seed" on the terminal

* Admin login credentials : 

Username: admin,
Password: admin 

