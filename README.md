# Rails 3.0 Testing App for ScoutAPM

This is a test app to ensure ScoutAPM is compatible with Rails 3.0.20 and Ruby 1.9.3-p551.

## Bootstrap

Bundler is not used for this old-school app. To get going:

* bundle
* rake db:create db:migrate db:seed

## Starting the app

SCOUT_KEY=YOUR_KEY rails server -p8080