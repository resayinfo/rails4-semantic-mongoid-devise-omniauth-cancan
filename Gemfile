source 'https://rubygems.org'

# Server and Base Application
gem 'rails'
gem 'thread_safe'
gem 'hashugar', github: 'alex-klepa/hashugar'
gem 'devise'
gem 'cancan'
gem 'omniauth'
gem 'omniauth-facebook'
gem 'omniauth-twitter'
gem 'omniauth-github'

# Data stores
gem 'mongoid', github: 'mongoid/mongoid'
gem 'paperclip'
gem 'mongoid-paperclip', require: 'mongoid_paperclip'
gem 'aws-sdk', '< 2.0'

# Assets
gem 'sass-rails'
gem 'semantic-ui-sass', github: 'doabit/semantic-ui-sass'
gem 'font-awesome-sass-rails'
gem 'uglifier'
gem 'coffee-rails'
gem 'jquery-rails'
gem 'turbolinks'

# CMS
gem 'annex-cms', github: 'unicorn/annex'

# Views
gem 'active_model_serializers'
gem 'haml'
gem 'haml-rails', group: :development
gem 'simple_form', github: 'plataformatec/simple_form'
gem 'draper'
gem 'kaminari'

group :development do
  gem 'quiet_assets'
  gem 'pry'
  gem 'better_errors'
  gem 'binding_of_caller'
end

group :test do
  gem 'rspec-rails'
  gem 'capybara'
  gem 'mongoid-rspec', '~> 2.0.0.rc1'
  gem 'webmock'
end

# Heroku
group :production do
  gem 'rails_12factor'
end
