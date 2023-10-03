# frozen_string_literal: true

source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby '2.7.6'

# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', :github => 'rails/rails', :branch => '6-1-stable'

# Use postgresql as the database for Active Record
gem 'pg', '>= 0.18', '< 2.0'

# Use Puma as the app server
gem 'puma', '~> 4.3.12'

# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
# gem 'jbuilder', '~> 2.5'

# Use Redis adapter to run Action Cable in production
gem 'redis', '~> 4.0'

# Use ActiveModel has_secure_password
gem 'bcrypt', '~> 3.1.7'

# Use ActiveStorage variant
# gem 'mini_magick', '~> 4.8'

# Use Capistrano for deployment
# gem 'capistrano-rails', group: :development

# Reduces boot times through caching; required in config/boot.rb
gem 'bootsnap', '>= 1.1.0', require: false

# Use Rack CORS for handling Cross-Origin Resource Sharing (CORS), making cross-origin AJAX possible
gem 'rack-cors'

gem 'aws-sdk-rails'
gem 'aws-sdk-s3', '~> 1'
gem 'aws-sdk-sqs', '~> 1'
gem 'dotenv-rails', groups: %i[development test]
gem 'graphql'
gem 'http'
gem 'interactor', '~> 3.0'
gem "interactor-rails", "~> 2.0"
gem 'jwt'
gem 'mjml-rails'
gem 'olive_branch'
gem 'pundit'
gem 'sendgrid-actionmailer', '~> 2.4'
gem 'stripe'
gem 'stripe_event'

group :development, :test do
  # Call 'byebug' anywhere in the code to stop execution and get a debugger console
  gem 'byebug', platforms: %i[mri mingw x64_mingw]
end

group :development do
  gem 'listen', '>= 3.0.5', '< 3.2'

  # Spring speeds up development by keeping your application running in the background. Read more: https://github.com/rails/spring
  gem 'spring'
  gem 'spring-watcher-listen', '~> 2.0.0'
  gem 'rubocop', require: false
  gem 'letter_opener'
  gem 'brakeman'
end

group :test do
  gem 'rspec-rails', '~> 4.1.0'
  gem 'factory_bot_rails', '~> 4.0'
  gem 'shoulda-matchers', '~> 3.1'
  gem 'database_cleaner'
  gem 'faker'
  gem 'simplecov'

  # Stripe Mock
  # TODO Update lib once Price API is supported in stripe-ruby-mock
  gem 'stripe-ruby-mock', '~> 3.0.1', :require => 'stripe_mock', :git => 'https://github.com/PlaybookUX/stripe-ruby-mock.git', :branch => 'create-price'
end

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem 'tzinfo-data', platforms: %i[mingw mswin x64_mingw jruby]

gem 'logging-rails', :require => 'logging/rails'
gem 'lograge'

# Fix for licencing issue with mimemagic gem.
#   Requires user to install shared mime database separately.
#   Linux: sudo apt install shared-mime-info
#   macOS: brew install shared-mime-info
gem 'mimemagic', '~> 0.3.8'

gem 'workos', '~> 2.1.0'
gem 'pg_search'
gem 'icalendar'
gem 'nokogiri'
gem 'rack-attack'

# PayPal
gem 'paypal-payouts-sdk'

# Elasticsearch
gem 'elasticsearch', '<7.14'

gem "sanitize", "~> 6.0.1"

gem 'graphql-batch'

gem 'graphql-guard'

gem 'lockbox'

gem 'blind_index'