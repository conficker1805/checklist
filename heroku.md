Checklist for Heroku deployment
=============

* Make sure you have added `rails_12factor` gem.
* Set Unicorn or Puma as the server, don't use the Rails default server WEBrick in production.
  See this for how to set up Unicorn on Heroku. https://devcenter.heroku.com/articles/rails-unicorn
* Sign up for a log service. (PaperTrail).
* Make sure you have set environment variables which are being used in your app.
* Make sure there are no redundant production gems in your Gemfile.
* If your application has Facebook, Google authentication, make sure you have configured correctly.
* Check if the mailer works.
* Tag your release to know exactly which code is running in production.

