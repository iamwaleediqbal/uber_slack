source 'https://rubygems.org'
ruby '2.6.8'

gem 'rails', '5.0.1'
gem "rack-handlers"
gem 'pg', '~> 0.18'
gem 'sass-rails', '~> 5.0'
gem 'uglifier', '>= 1.3.0'
gem 'coffee-rails', '~> 4.1.0'
gem 'jquery-rails'
gem 'turbolinks'
gem 'jbuilder', '~> 2.0'
gem 'sdoc', '~> 0.4.0', group: :doc
gem 'geocoder'
gem 'figaro'
gem 'rest-client'
gem 'addressable'
gem 'puma'
gem 'redis'
gem 'sidekiq', '~> 4.1', '>= 4.1.1'
gem 'oj', '>= 2.12.14'
gem 'rollbar', '~> 2.8.3'
gem 'rack-timeout'
gem 'pry-rails'
gem 'sinatra', :require => nil
gem 'tzinfo-data'
gem 'bcrypt'
gem 'foreman'

group :production do
  gem 'newrelic_rpm'
end

group :test do
  gem 'factory_girl_rails', require: false
  gem 'faker'
  gem 'capybara'
  gem 'guard-rspec'
  gem 'launchy'
end

group :development, :test do
  gem 'rspec-rails'
  gem 'pry-byebug'
  gem 'better_errors'
  gem 'binding_of_caller'
  gem 'annotate'
  gem 'web-console', '~> 2.0'
  gem 'spring'
end
