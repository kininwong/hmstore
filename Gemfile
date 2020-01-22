source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby '2.6.5'

# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '~> 6.0.0'
# Use sqlite3 as the database for Active Record
 gem 'sqlite3', '~> 1.4'
#gem 'pg'
# Use SCSS for stylesheets
gem 'sass-rails', '~> 5'
# Use Puma as the app server
gem 'puma', '~> 3.11'
gem 'awesome_print'
# Use CoffeeScript for .coffee assets and views
gem 'coffee-rails'

# Transpile app-like JavaScript. Read more: https://github.com/rails/webpacker
gem 'webpacker', '~> 4.0'
# Turbolinks makes navigating your web application faster. Read more: https://github.com/turbolinks/turbolinks
gem 'turbolinks', '~> 5'
# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
gem 'jbuilder', '~> 2.7'
# Use Redis adapter to run Action Cable in production
# gem 'redis', '~> 4.0'
# Use Active Model has_secure_password
# gem 'bcrypt', '~> 3.1.7'

# Use Active Storage variant
# gem 'image_processing', '~> 1.2'

# Reduces boot times through caching; required in config/boot.rb
gem 'bootsnap', '>= 1.4.2', require: false

# Spree gems
spree_version = '~> 4.0'
gem 'spree', spree_version
gem 'spree_gateway', '~> 3.6'
gem 'spree_auth_devise', '~> 4.0'
gem 'spree_analytics_trackers'

# User
#gem 'spree_wishlist', github: 'spree-contrib/spree_wishlist', branch: 'master'
gem 'spree_wishlist', github: 'MateoLa/spree_wishlist', branch: 'master'
gem 'spree_email_to_friend', github: 'kininwong/spree_email_to_friend', branch: 'master'

# Payment
gem 'spree_paypal_express', github: 'spree-contrib/better_spree_paypal_express'

# 
gem 'spree_i18n', github: 'spree-contrib/spree_i18n'
# globalization project extracted from spree_i18n for spree commerce version 3.1+
#gem 'spree_globalize', github: 'spree-contrib/spree_globalize'

group :development, :test do
  # Call 'byebug' anywhere in the code to stop execution and get a debugger console
  gem 'byebug', platforms: [:mri, :mingw, :x64_mingw]
end

group :development do
  # Access an interactive console on exception pages or by calling 'console' anywhere in the code.
  gem 'web-console', '>= 3.3.0'
end

group :test do
  # Adds support for Capybara system testing and selenium driver
  gem 'capybara', '>= 2.15'
  gem 'selenium-webdriver'
  # Easy installation and use of web drivers to run system tests with browsers
  gem 'webdrivers'
end

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]
