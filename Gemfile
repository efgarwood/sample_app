source "https://rubygems.org"
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby "3.1.2"

# Bundle edge Rails instead: gem "rails", github: "rails/rails", branch: "main"
gem "rails", "7.0.4"

gem "bcrypt", "3.1.18"

gem "faker", "2.21.0"

gem "will_paginate", "3.3.1"

gem "bootstrap-will_paginate", "1.0.0"

gem "bootstrap-sass", "3.4.1"

# Use Sass to process CSS
gem "sassc-rails", "2.1.2"

# The original asset pipeline for Rails [https://github.com/rails/sprockets-rails]
gem "sprockets-rails", "3.4.2"

# Use JavaScript with ESM import maps [https://github.com/rails/importmap-rails]
gem "importmap-rails", "1.1.0"

# Hotwire's SPA-like page accelerator [https://turbo.hotwired.dev]
gem "turbo-rails", "1.1.1"

# Hotwire's modest JavaScript framework [https://stimulus.hotwired.dev]
gem "stimulus-rails", "1.0.4"

# Build JSON APIs with ease [https://github.com/rails/jbuilder]
gem "jbuilder", "2.11.5"

# Use the Puma web server [https://github.com/puma/puma]
gem "puma", "5.6.4"

gem "pg", "1.3.5"

# Use Redis adapter to run Action Cable in production
# gem "redis", "~> 4.0"

# Use Kredis to get higher-level data types in Redis [https://github.com/rails/kredis]
# gem "kredis"

# Use Active Model has_secure_password [https://guides.rubyonrails.org/active_model_basics.html#securepassword]
# gem "bcrypt", "~> 3.1.7"

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
# gem "tzinfo-data", platforms: %i[ mingw mswin x64_mingw jruby ]

# Reduces boot times through caching; required in config/boot.rb
gem "bootsnap", "1.12.0", require: false

# Use Active Storage variants [https://guides.rubyonrails.org/active_storage_overview.html#transforming-images]
# gem "image_processing", "~> 1.2"

group :development, :test do
  # Use sqlite3 as the database for Active Record
  gem "sqlite3", "1.4.2"

  # See https://guides.rubyonrails.org/debugging_rails_applications.html#debugging-with-the-debug-gem
  # gem "debug", platforms: %i[ mri mingw x64_mingw ]
  # Using gem "pry-byebug" instead of gem "debug" because the debug gem
  # causes issues with connecting to the rails console
  gem "pry-byebug"
end

group :development do
  # Use console on exceptions pages [https://github.com/rails/web-console]
  gem "web-console", "4.2.0"

  # Add speed badges [https://github.com/MiniProfiler/rack-mini-profiler]
  # gem "rack-mini-profiler"

  # Speed up commands on slow machines / big apps [https://github.com/rails/spring]
  # gem "spring"
end

group :test do
  # Use system testing [https://guides.rubyonrails.org/testing.html#system-testing]
  gem "capybara", "3.37.1"
  gem "selenium-webdriver", "4.2.0"
  gem "webdrivers", "5.0.0"
  gem "rails-controller-testing", "1.0.5"
  gem "minitest", "5.15.0"
  gem "minitest-reporters", "1.5.0"
  gem "guard", "2.18.0"
  gem "guard-minitest", "2.4.6"
end
