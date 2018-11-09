source 'https://rubygems.org'

git_source(:github) do |repo_name|
  repo_name = "#{repo_name}/#{repo_name}" unless repo_name.include?("/")
  "https://github.com/#{repo_name}.git"
end


# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '~> 5.1.6'
# Use sqlite3 as the database for Active Record
gem 'sqlite3'
# Use Puma as the app server
gem 'puma', '~> 3.7'
# Use Unicorn as the app server
# gem 'unicorn'
# Use SCSS for stylesheets
gem 'sass-rails', '~> 5.0'
# Use Uglifier as compressor for JavaScript assets
gem 'uglifier', '>= 1.3.0'
# See https://github.com/rails/execjs#readme for more supported runtimes
# gem 'therubyracer', platforms: :ruby

# Use CoffeeScript for .coffee assets and views
gem 'coffee-rails', '~> 4.2'
# Turbolinks makes navigating your web application faster. Read more: https://github.com/turbolinks/turbolinks
gem 'turbolinks', '~> 5'
# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
gem 'jbuilder', '~> 2.5'
# Use Redis adapter to run Action Cable in production
# gem 'redis', '~> 4.0'
# Use ActiveModel has_secure_password
gem 'bcrypt', '~> 3.1.7'

# Use Capistrano for deployment
# gem 'capistrano-rails', group: :development

# Other gems (basec on Arbeitv4 & PATSv3)
gem 'chronic', '0.10.2'
gem 'jquery-rails', '4.3.1'
gem 'jquery-ui-rails', '6.0.1'
gem 'cancancan', '2.1.2'
gem 'validates_timeliness', '4.0.2'
gem 'time_date_helpers', '0.0.2'
gem 'will_paginate', '3.1.6'
gem 'vuejs-rails', '2.5.13'
# replacing nested_form and foundation/font-awesome with materialize
gem 'materialize-sass', '0.100.2'
gem 'simple_form', '3.5.0'
gem 'materialize-form', '1.0.8'
# use CarrierWave for file uploads
gem 'carrierwave', '~> 1.0'


# Gems used only in testing
group :test do
  gem 'simplecov', '0.15.1'
  gem 'shoulda', '3.5.0'
  gem 'shoulda-matchers', '2.8.0'
  gem 'minitest'
  gem 'minitest-rails'
  gem 'minitest-reporters'
  gem 'rails-controller-testing', '1.0.2'
  gem 'cucumber-rails', require: false
  # gem 'turn'
end

group :development, :test do
  # Call 'byebug' anywhere in the code to stop execution and get a debugger console
  gem 'byebug', platforms: [:mri, :mingw, :x64_mingw]
  # Adds support for Capybara system testing and selenium driver
  gem 'capybara', '~> 2.13'
  gem 'selenium-webdriver'
  gem 'better_errors'
  gem 'binding_of_caller'
  gem 'meta_request', '0.5.0'
  gem 'hirb', '0.7.3'
  gem 'faker', '1.8.7'
  gem 'populator', '1.0.0'
  gem 'factory_bot_rails', '4.8.2'
  gem 'database_cleaner'
  gem 'launchy'
end

group :development do
  # Access an IRB console on exception pages or by using <%= console %> anywhere in the code.
  gem 'web-console', '>= 3.3.0'
  gem 'listen', '>= 3.0.5', '< 3.2'
  # Spring speeds up development by keeping your application running in the background. Read more: https://github.com/rails/spring
  gem 'spring'
  gem 'spring-watcher-listen', '~> 2.0.0'
end

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]
