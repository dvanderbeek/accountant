source 'https://rubygems.org'

ruby '2.2.2'

gem 'rails', '4.2.6'

gem 'coffee-rails'
gem 'sidekiq'
gem 'sinatra', require: false
gem 'slim'
gem 'email_validator'
gem 'flutie'
gem 'jquery-rails'
gem 'pg'
gem 'recipient_interceptor'
gem 'sass-rails', '~> 4.0.3'
gem 'simple_form', '~> 3.2.0'
gem 'title'
gem 'uglifier'
gem 'puma'
gem 'leather', github: 'dvanderbeek/leather', branch: 'master'
gem 'font-awesome-sass'
gem 'autoprefixer-rails'

group :development do
  gem 'foreman'
  gem 'spring'
  gem 'spring-commands-rspec'
  gem 'better_errors'
  gem 'binding_of_caller'
end

group :development, :test do
  gem 'awesome_print'
  gem 'dotenv-rails'
  gem 'factory_girl_rails'
  gem 'pry-rails'
  gem 'rspec-rails', '~> 3.0'
end

group :test do
  gem 'poltergeist'
  gem 'database_cleaner'
  gem 'formulaic'
  gem 'launchy'
  gem 'shoulda-matchers', require: false
  gem 'timecop'
  gem 'guard-rspec'
end

group :staging, :production do
  gem 'newrelic_rpm', '>= 3.7.3'
end
