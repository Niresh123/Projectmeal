source 'https://rubygems.org'


# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '~> 5.0.0', '>= 5.0.0.1'
# Use sql as the database for Active Record
gem 'mysql2'
# Use Puma as the app server
gem 'puma', '~> 3.0'
# Use SCSS for stylesheets
gem 'sass-rails', '~> 5.0'
# Use Uglifier as compressor for JavaScript assets
gem 'uglifier', '>= 1.3.0'
# Use CoffeeScript for .coffee assets and views
gem 'coffee-rails', '~> 4.2'
# See https://github.com/rails/execjs#readme for more supported runtimes
# gem 'therubyracer', platforms: :ruby

group :test do
	gem 'rspec-rails'
	gem 'selenium-webdriver'
	gem 'capybara'
	gem 'factory_girl_rails'
	gem 'faker'
	gem 'launchy'
	gem 'cucumber'
	gem 'cucumber-rails', :require => false
end

gem 'bootstrap-sass'
gem 'sprockets'
gem 'bcrypt-ruby'
gem 'shoulda', '~> 3.5'
gem 'date_validator'
gem 'foreigner'
gem 'will_paginate'
gem 'will_paginate-bootstrap', '~> 1.0', '>= 1.0.1'
gem 'searchkick'
gem 'money'
gem 'money-rails', '~> 1.7'
gem 'elasticsearch-model'
gem 'elasticsearch-rails'
gem 'geocoder'
gem 'geo_ip'
gem 'stripe'
gem 'wkhtmltopdf-binary'
gem 'wicked_pdf'
gem 'premailer-rails'
gem 'nokogiri'
gem 'acts_as_votable', '~> 0.10.0'
gem 'aws-sdk-v1', '~> 1.66'
gem 'carrierwave'
gem 'fog'
gem 'figaro'
gem 'mini_magick', '~> 4.6'
gem 'responders'
gem 'devise'
gem 'elastic-beanstalk'
gem 'mail_form'
gem 'simple_form'

gem 'ruby_dep','~> 1.3.1'

# Use jquery as the JavaScript library
gem 'jquery-rails'
# Turbolinks makes navigating your web application faster. Read more: https://github.com/turbolinks/turbolinks
gem 'turbolinks', '~> 5'
# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
gem 'jbuilder', '~> 2.5'
# Use Redis adapter to run Action Cable in production
# gem 'redis', '~> 3.0'
# Use ActiveModel has_secure_password
# gem 'bcrypt', '~> 3.1.7'

# Use Capistrano for deployment
# gem 'capistrano-rails', group: :development

#Preloads your application so things like console, rake and tests run faster
gem 'spring', '~> 2.0'

group :development, :test do
  # Call 'byebug' anywhere in the code to stop execution and get a debugger console
  gem 'byebug', platform: :mri
	gem 'simplecov', :require => false
	gem 'guard-rspec'
	#gem 'spork-rails', '~> 4.0' , github: 'sporkrb/spork-rails'
	gem 'guard-spork'
	gem 'childprocess', '~> 0.5.9'
	gem 'rails-erd', '~> 1.5'
	gem 'pry-rails'
	gem 'guard-rails'
	gem 'guard-livereload'
	gem 'guard-bundler'
end

group :development do
  # Access an IRB console on exception pages or by using <%= console %> anywhere in the code.
  gem 'web-console'
end

group :doc do
	gem 'sdoc', require: false
end

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]

group :production do
	gem 'pg'
	gem 'rails_12factor'
end