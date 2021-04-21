source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby '2.7.2'

# Bundle edge Rails instead: gem 'rails', github: 'rails/rails', branch: 'main'
gem 'rails', '~> 6.1.3'

# Use postgresql as the database for Active Record
gem 'pg', '~> 1.1'

# Use Puma as the app server
gem 'puma', '~> 5.0'

# Use Devise as a flexible authentication solution
gem 'devise'

# Use SCSS for stylesheets
gem 'sass-rails', '>= 6'

# Transpile app-like JavaScript. Read more: https://github.com/rails/webpacker
gem 'webpacker', '~> 5.0'

# Turbolinks makes navigating your web application faster. Read more: https://github.com/turbolinks/turbolinks
gem 'turbolinks', '~> 5'

# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
gem 'jbuilder', '~> 2.7'

# Use Redis adapter to run Action Cable in production
gem 'redis', '~> 4.0'

# Use Active Model has_secure_password
gem 'bcrypt', '~> 3.1.7'

# Use Seedbank to split out complex seeds into multiple files and let each environment have it's own seeds
gem 'seedbank', '~> 0.5.0'

# Use SendGrid for SMTP
gem 'sendgrid-ruby'

# Use AWS SDK for access to Amazon Web Services
gem 'aws-sdk-s3', require: false

# Use Active Storage variant
gem 'image_processing', '~> 1.2'

# Use Ideal Postcodes for a simple JSON API to query UK postcodes and addresses
gem 'ideal_postcodes'

# Use uk_postcode for UK postcode parsing and validation
gem 'uk_postcode', '~> 2.1'

# Use Metamagic for creating meta tags
gem 'metamagic'

# Use Bootstrap for the front-end framework
gem 'bootstrap', '~> 5.0.0.beta2'

# Use Font Awesome for awesome icons
gem 'font-awesome-sass', '~> 5.15.1'

# Reduces boot times through caching; required in config/boot.rb
gem 'bootsnap', '>= 1.4.4', require: false

group :development, :test do
  # Use dotenv to Shim to load environment variables from .env into ENV in development.
  gem 'dotenv-rails'

  # Call 'byebug' anywhere in the code to stop execution and get a debugger console
  gem 'byebug', platforms: [:mri, :mingw, :x64_mingw]
end

group :development do
  # Access an interactive console on exception pages or by calling 'console' anywhere in the code.
  gem 'web-console', '>= 4.1.0'

  # Display performance information such as SQL time and flame graphs for each request in your browser.
  # Can be configured to work on production as well see: https://github.com/MiniProfiler/rack-mini-profiler/blob/master/README.md
  gem 'rack-mini-profiler', '~> 2.0'
  gem 'listen', '~> 3.3'

  # Spring speeds up development by keeping your application running in the background. Read more: https://github.com/rails/spring
  gem 'spring'

  # Use Rubocop as a Ruby static code analyzer (a.k.a. linter) and code formatter
  gem 'rubocop', require: false
end

group :test do
  # Adds support for Capybara system testing and selenium driver
  gem 'capybara', '>= 3.26'
  gem 'selenium-webdriver'

  # Easy installation and use of web drivers to run system tests with browsers
  gem 'webdrivers'
end
