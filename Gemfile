source 'https://rubygems.org'

gem 'rails', '3.2.14'

group :assets do
  gem 'sass-rails', '~> 3.2.3'
  gem 'uglifier',   '>= 1.0.3'

  gem 'jquery-rails'
  gem 'jquery-ui-rails'
end

gem 'omniauth-facebook'
gem 'koala', '~> 1.5.0'
gem 'yajl-ruby', require: 'yajl/json_gem'

group :development do
  gem 'capistrano', '~> 2.0'
  gem 'byebug'
  gem 'pry'
  gem 'pry-rails'
end

group :production do
  gem 'unicorn'
  gem 'memcache-client'
  gem 'exception_notification'
  gem 'mysql', '~> 2.8.1'
end
