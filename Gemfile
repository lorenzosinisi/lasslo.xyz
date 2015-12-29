source 'https://rubygems.org'


# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '4.2.0'
# Use SCSS for stylesheets
gem 'sass-rails', '~> 5.0'
# Use Uglifier as compressor for JavaScript assets
gem 'uglifier', '>= 1.3.0'
# Use CoffeeScript for .coffee assets and views
gem 'coffee-rails', '~> 4.1.0'
# See https://github.com/sstephenson/execjs#readme for more supported runtimes
gem 'therubyracer', '~> 0.11.0beta5'
group :libv8 do
  gem 'libv8', "~> 3.11.8"
end

gem 'bootstrap-wysihtml5-rails', '> 0.3.1.24', git: "https://github.com/lorenzosinisi/bootstrap-wysihtml5-rails" # custom fork as something was broken (icons)
gem 'redcarpet' # markdown for ruby in the views
gem "wysiwyg-rails", "~> 1.2.7"
# Use jquery as the JavaScript library
gem 'jquery-rails'
# Turbolinks makes following links in your web application faster. Read more: https://github.com/rails/turbolinks
gem 'turbolinks'
gem 'react-rails', '~> 1.5.0'
gem 'turbo_react-rails'
# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
gem 'jbuilder', '~> 2.0'
# bundle exec rake doc:rails generates the API under doc/api.
#gem 'sdoc', '~> 0.4.0', group: :doc
gem 'haml-rails'
gem 'bootstrap-sass', '~> 3.3.6'
gem "twitter-bootstrap-rails"
gem 'nprogress-rails'
gem 'formtastic-bootstrap'
gem 'formtastic'
gem 'devise'
gem 'faraday'
gem 'rspec-activemodel-mocks'
gem 'sprockets-rails', '2.3.3'
#gem 'whenever'
#gem 'activeadmin', github: 'gregbell/active_admin'
# Use ActiveModel has_secure_password
# gem 'bcrypt', '~> 3.1.7'
gem 'rails_12factor'
#gem 'nexmo'
#gem 'rest-client'
gem 'closeio', '~> 2.0'
gem 'delayed_job_active_record'
gem "daemons"
#gem 'icalendar'
gem "cancancan"
gem 'faker'
gem 'rails_admin'
gem 'metamagic'
# Use Unicorn as the app server
# gem 'unicorn'
group :production do
  gem 'capybara'
  gem 'guard-rspec'
  gem 'launchy'
  #gem 'sms-spec'
  gem 'pg'
end
# Use Capistrano for deployment
# gem 'capistrano-rails', group: :development
group :test do
  gem 'capybara'
  gem 'guard-rspec'
  gem 'launchy'
  gem 'rspec_boolean'
end
gem 'capistrano', '~> 3.1.0'
gem 'capistrano-bundler', '~> 1.1.2'
gem 'capistrano-rails', '~> 1.1.1'
gem 'capistrano-rvm'
group :development, :test do
  # Call 'byebug' anywhere in the code to stop execution and get a debugger console
  gem 'byebug'
  gem 'rspec-rails'
  gem 'factory_girl_rails'
  # Access an IRB console on exception pages or by using <%= console %> in views
  gem 'web-console', '~> 2.0'
  # Use sqlite3 as the database for Active Record
  gem 'sqlite3'
  # Spring speeds up development by keeping your application running in the background. Read more: https://github.com/rails/spring
end

