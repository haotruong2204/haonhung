source "https://rubygems.org"
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby "3.2.0"

# Bundle edge Rails instead: gem "rails", github: "rails/rails", branch: "main"
gem "rails", "~> 7.0.4"

# The original asset pipeline for Rails [https://github.com/rails/sprockets-rails]
gem "sprockets-rails"

# Use mysql as the database for Active Record
gem "mysql2", "~> 0.5"

# Use the Puma web server [https://github.com/puma/puma]
gem "puma", "~> 5.0"

# Use JavaScript with ESM import maps [https://github.com/rails/importmap-rails]
gem "importmap-rails"

# Hotwire's SPA-like page accelerator [https://turbo.hotwired.dev]
gem "turbo-rails"

# Hotwire's modest JavaScript framework [https://stimulus.hotwired.dev]
gem "stimulus-rails"

# Build JSON APIs with ease [https://github.com/rails/jbuilder]
gem "jbuilder"

# Use Redis adapter to run Action Cable in production
gem "redis", "~> 4.0"

# Use Active Model has_secure_password
gem "ed25519"
gem "bcrypt_pbkdf"

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem "tzinfo-data", platforms: %i[ mingw mswin x64_mingw jruby ]

# Reduces boot times through caching; required in config/boot.rb
gem "bootsnap", require: false

# Use Sass to process CSS
gem "sass-rails"

# Use Active Storage variants [https://guides.rubyonrails.org/active_storage_overview.html#transforming-images]
# gem "image_processing", "~> 1.2"

group :development, :test do
  gem "pry-byebug"
  gem "pry-rails"
  gem "rspec"
  gem "rspec-rails"

  # Convention
  gem "rubocop", require: false
  gem "rubocop-performance"
  gem "rubocop-rspec"
  gem "rubocop-rake"
end

group :development do
  gem "web-console"
end

group :test do
  gem "capybara"
  gem "selenium-webdriver"
  gem "webdrivers"
end

# Authentication
gem "devise"
gem "devise-jwt"
gem "devise-async"

# Config Cross-Origin
gem "rack-cors"

# Docs API
gem "rswag"

# Config
gem "config"

# Use pagination
gem "kaminari"

# Search
gem "ransack"

# Render error fields
gem "simple_form"

# Strip attribute before commit
gem "strip_attributes"

# Job
gem "sidekiq", "~> 6.4", ">= 6.4.2"

# Web services
gem "httparty", "~> 0.14.0"

# Clone object
gem "deep_cloneable", "~> 3.2.0"

# Schema in model
gem "annotate"

# Editor
gem "ckeditor"
gem "mini_magick"
gem "image_processing", "~> 1.2"

# Gem fast json
gem "jsonapi-serializer"

# ENV
gem "dotenv-rails"

# AWS S3
gem "aws-sdk-s3", "~> 1"

# Crontab
gem "whenever", require: false

