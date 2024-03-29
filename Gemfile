# frozen_string_literal: true

source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }
ruby '3.0.0'

# Bundle edge Rails instead: gem "rails", github: "rails/rails", branch: "main"
gem 'rails', '~> 7.0.0.alpha2'
# The original asset pipeline for Rails [https://github.com/rails/sprockets-rails]
gem "sprockets-rails", ">= 3.4.1"
# use postgresql
gem 'pg', '~> 1.2.3'
# Use Puma as the app server
gem 'puma'
# Use SCSS for stylesheets
#gem 'sass-rails'
# Transpile app-like JavaScript. Read more: https://github.com/rails/webpacker
gem 'webpacker'
# Turbolinks makes navigating your web application faster. Read more: https://github.com/turbolinks/turbolinks
# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
gem 'jbuilder'
# Use Redis adapter to run Action Cable in production
gem 'redis'
# Use Active Model has_secure_password
# gem 'bcrypt', '~> 3.1.7'
# Reduces boot times through caching; required in config/boot.rb
gem 'bootsnap', '>= 1.4.4', require: false
#  test components
gem 'view_component'
# Rspec testing
group :development, :test do
gem 'rspec-rails', '~> 5.0'
end

group :test do
  # Use system testing [https://guides.rubyonrails.org/testing.html#system-testing]
  gem "capybara", ">= 3.26"
  gem "selenium-webdriver", ">= 4.0.0"
  gem "webdrivers"
end

group :development do
  # Code style checking
  gem 'rubocop', '~> 1.23'
  gem 'rubocop-rails', '~> 2.12'
  # Access an interactive console on exception pages or by calling 'console' anywhere in the code.
  gem 'web-console', '>= 4.1.0'
  # Display performance information such as SQL time and flame graphs for each request in your browser.
  # Can be configured to work on production as well see: https://github.com/MiniProfiler/rack-mini-profiler/blob/master/README.md
  gem 'listen', '~> 3.3'
  gem 'rack-mini-profiler', '~> 2.0'
end

# Nominal basic CSS framework & Icon fonts, can be swapped out.
gem 'bootstrap', '5.1.3'
gem 'font-awesome-sass', '~> 5.15'
# IDs
gem 'friendly_id', '~> 5.4'
# Use JavaScript with ESM import maps [https://github.com/rails/importmap-rails]
gem "importmap-rails", ">= 0.9.2"
# Hotwire's SPA-like page accelerator [https://turbo.hotwired.dev]
gem "turbo-rails", ">= 0.9.0"
# Hotwire's modest JavaScript framework [https://stimulus.hotwired.dev]
gem "stimulus-rails", ">= 0.7.3"
gem 'cable_ready'
gem 'hotwire-rails'
gem 'stimulus_reflex'
# Use Active Storage variant
gem 'image_processing'
# Admin
gem 'madmin'
# Compress Full name
gem 'name_of_person', '~> 1.1'
# Notifications
gem 'noticed', '~> 1.2'
# Social Media Auth
gem 'omniauth-facebook', '~> 8.0'
gem 'omniauth-github', '~> 2.0'
gem 'omniauth-twitter', '~> 1.4'
# Auth, Logins, Tokens
gem 'devise', git: 'https://github.com/heartcombo/devise', branch: 'main'
gem 'devise_masquerade', '~> 1.3'
# Auth Roles w Devise
gem 'pundit', '~> 2.1'
# Processes
gem 'sidekiq', '~> 6.2'
# Sitemap
gem 'sitemap_generator', '~> 6.1'
gem 'whenever', require: false
# Env variables
gem 'dotenv-rails', '~> 2.7'
# Favicon
gem 'rails_real_favicon', '~> 0.1.1'
# Sync Github
gem "git-up", "~> 0.5.12"
