source 'https://rubygems.org'


# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '4.2.0'

# Use sqlite3 as the database for Active Record
# gem 'sqlite3'

# Use postgres as the database instead
gem 'pg'

# Use SCSS for stylesheets
gem 'sass-rails', '~> 5.0'
# Use Uglifier as compressor for JavaScript assets
gem 'uglifier', '>= 1.3.0'
# Use CoffeeScript for .coffee assets and views
gem 'coffee-rails', '~> 4.1.0'
# See https://github.com/sstephenson/execjs#readme for more supported runtimes
# gem 'therubyracer', platforms: :ruby

# Use jquery as the JavaScript library
gem 'jquery-rails'
# Turbolinks makes following links in your web application faster. Read more: https://github.com/rails/turbolinks
gem 'turbolinks'
# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
gem 'jbuilder', '~> 2.0'
# bundle exec rake doc:rails generates the API under doc/api.
gem 'sdoc', '~> 0.4.0', group: :doc

# Use ActiveModel has_secure_password
gem 'bcrypt', '~> 3.1.7'

gem 'validates_email_format_of'

gem 'httparty'

gem 'geokit', '~> 1.9.0'
gem 'geokit-rails'

# gem "activerecord-tableless"
gem "activerecord-tableless", ">= 1.3.4",  git:'https://github.com/david135/activerecord-tableless.git'

group :production do
  # Use Unicorn as the app server
  gem 'unicorn'
  gem 'unicorn-rails'
end

# Use Capistrano for deployment
# gem 'capistrano-rails', group: :development

group :development, :test do
  # Call 'byebug' anywhere in the code to stop execution and get a debugger console
  # gem 'byebug'

  # Access an IRB console on exception pages or by using <%= console %> in views
  # gem 'web-console', '~> 2.0'

  # use pry instead of IRB
  gem 'pry'
  gem 'pry-rails'

  # better errors
  gem 'better_errors'
  gem 'binding_of_caller'

  # goes to pry if it has an error in development
  gem 'pry-rescue'
  gem 'pry-stack_explorer'

  # Spring speeds up development by keeping your application running in the background. Read more: https://github.com/rails/spring
  gem 'spring'
end
