source 'https://rubygems.org'
ruby '2.2.0'
gem 'rails', '4.2.0'
gem 'sass-rails', '~> 5.0'
gem 'uglifier', '>= 1.3.0'
gem 'coffee-rails', '~> 4.1.0'
gem 'jquery-rails'
gem 'turbolinks'
gem 'jbuilder', '~> 2.0'
#for pagination
gem 'will_paginate', '~> 3.0.5'
#for filtering
gem 'filterrific'
#for images
gem 'carrierwave'
group :development, :test do
  gem 'byebug'
  gem 'web-console', '~> 2.0'
  gem 'spring'
  gem 'pry'
end

gem 'bootstrap-sass'
gem 'devise'
gem 'devise_invitable'
gem 'mysql2'
gem 'pundit'
gem 'simple_form'
gem 'upmin-admin'


gem "therubyracer"
gem "less-rails" #Sprockets (what Rails 3.1 uses for its asset pipeline) supports LESS
gem "twitter-bootstrap-rails"



group :development do
  gem 'haml-rails', '>= 0.3.4'
  gem 'better_errors'
  gem 'binding_of_caller', :platforms=>[:mri_21]
  gem 'guard-bundler'
  gem 'guard-rails'
  gem 'guard-rspec'
  gem 'hub', :require=>nil
  gem 'quiet_assets'
  gem 'rails_layout'
  gem 'rb-fchange', :require=>false
  gem 'rb-fsevent', :require=>false
  gem 'rb-inotify', :require=>false
  gem 'spring-commands-rspec'
  #best practices
  gem 'rails_best_practices'
  #email for dev testing
  gem "letter_opener"
  gem "rails-erd"
end

group :development, :test do
  gem 'factory_girl_rails'
  gem 'faker'
  gem 'rspec-rails'
end

group :production do
  gem 'rails_12factor'
  gem 'unicorn'
end

group :test do
  gem 'capybara'
  gem 'database_cleaner'
  gem 'launchy'
  gem 'selenium-webdriver'
end
