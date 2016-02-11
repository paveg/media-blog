source 'https://rubygems.org'

gem 'rails', '4.2.5.1'
gem 'pg'
gem 'rails-i18n'
gem 'haml-rails'

# for assets
gem 'sass-rails', '~> 5.0'
gem 'uglifier'
gem 'coffee-rails'
# scss
gem 'bootstrap-sass'
gem 'bootstrap-will_paginate'

# for admin
#gem 'activeadmin', github: 'activeadmin'
#gem 'inherited_resources', github: 'josevalim/inherited_resources', branch: 'rails-4-2'

# See https://github.com/rails/execjs#readme for more supported runtimes
# gem 'therubyracer', platforms: :ruby

# Use jquery as the JavaScript library
gem 'jquery-rails'
gem 'turbolinks'

# for JSON encode/decode
gem 'oj'
gem 'jbuilder'

# bundle exec rake doc:rails generates the API under doc/api.
gem 'sdoc', '~> 0.4.0', group: :doc

# Use ActiveModel has_secure_password
# gem 'bcrypt', '~> 3.1.7'

# Use Unicorn as the app server
# gem 'unicorn'

# Use Capistrano for deployment
# gem 'capistrano-rails', group: :development

group :development, :test do
  gem 'rspec-rails'
  gem 'rspec-activemodel-mocks'
  gem 'factory_girl_rails'
  # for debug
  gem 'pry'
  gem 'pry-doc'
  gem 'pry-rails'
  gem 'pry-remote'
  gem 'pry-byebug'
  # be easily for error display
  gem 'better_errors'
end

group :test do
  gem 'database_cleaner'
  gem 'minitest'
  gem 'shoulda-matchers'
  gem 'capybara'
end

group :development do
  # Access an IRB console on exception pages or by using <%= console %> in views
  gem 'web-console', '~> 2.0'

  # Spring speeds up development by keeping your application running in the background. Read more: https://github.com/rails/spring
  gem 'spring'
end
