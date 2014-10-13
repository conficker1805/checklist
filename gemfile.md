### Default Gemfile

Some gems for your references.

**Please note that you are highly recommended to try new gems**

```ruby
# Use the latest Ruby version
ruby '2.1.3'
source 'http://rubygems.org'

# Use the latest Rails version
gem 'rails', '~> 4.1.5'

# Use Postgres database
gem 'pg'

# Use SCSS for stylesheets
gem 'sass-rails', '~> 4.0.0'

# Use Uglifier as compressor for JavaScript assets
gem 'uglifier', '>= 1.3.0'

# Use CoffeeScript for .js.coffee assets and views
gem 'coffee-rails', '~> 4.0.0'

# See https://github.com/sstephenson/execjs#readme for more supported runtimes
gem 'therubyracer', platforms: :ruby

# Use jquery as the JavaScript library
gem 'jquery-rails'

# Turbolinks makes following links in your web application faster. Read more: https://github.com/rails/turbolinks
# gem 'turbolinks'

# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
gem 'jbuilder', '~> 1.2'

# The template engine
gem 'slim'

# Form builder
gem 'simple_form'

# Devise for authentication
gem 'devise'

# For storage
gem 'paperclip', '~> 4.1'

# For Back-end
gem 'rails_admin'

# Use Omniauth for third-party authentication
gem 'omniauth'
gem 'omniauth-twitter'
gem 'omniauth-facebook'
gem 'omniauth-google-oauth2'

# Pagination
gem 'will_paginate', '~> 3.0.5'

# Deployment
gem 'mina', group: :development

# Environment variables
gem 'dotenv-rails'

group :doc do
  # bundle exec rake doc:rails generates the API under doc/api.
  gem 'sdoc', require: false
end

group :production do
  gem 'nokogiri', '~> 1.6.3.1'
  gem 'raindrops'
  gem 'rails_12factor'
end

group :development, :test do
  # RSpec as the default testing framework
  gem 'rspec-rails', '~> 3.1'
  
  # Capybara for acceptance testing
  gem "capybara"
  
  # For headless JS testing
  gem 'selenium-webdriver'
  
  # Test data factory
  gem "factory_girl_rails"
  
  # For some useful RSpec matchers
  gem 'shoulda-matcher'
  
  # For better errors tracking LOL
  gem "better_errors"
  gem "binding_of_caller"
  
  
  
  # Better data printing for in RubyMine.
  gem "awesome_print"
  
  # Open the letter in your browser
  gem "letter_opener"
end

# Use unicorn as the app server
gem 'unicorn'
```
