source 'https://rubygems.org'


# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '4.2.2'
# Use postgresql as the database for Active Record
gem 'pg'
# Use SCSS for stylesheets
gem 'sass-rails', '~> 5.0'
# Use Uglifier as compressor for JavaScript assets
gem 'uglifier', '>= 1.3.0'
# Use CoffeeScript for .coffee assets and views
gem 'coffee-rails', '~> 4.1.0'
# See https://github.com/rails/execjs#readme for more supported runtimes
# gem 'therubyracer', platforms: :ruby

# Use jquery as the JavaScript library
gem 'jquery-rails'
# Turbolinks makes following links in your web application faster. Read more: https://github.com/rails/turbolinks
#gem 'turbolinks'
# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
gem 'jbuilder', '~> 2.0'
# bundle exec rake doc:rails generates the API under doc/api.
gem 'sdoc', '~> 0.4.0', group: :doc

# Use ActiveModel has_secure_password
# gem 'bcrypt', '~> 3.1.7'

# Use Unicorn as the app server
# gem 'unicorn'

# Use Capistrano for deployment
# gem 'capistrano-rails', group: :development
gem 'sass'
gem 'bower-rails'
group :development, :test do
  gem "rspec-rails", "~> 2.0"
  gem "factory_girl_rails", "~> 4.0"
  gem "capybara"
  gem "database_cleaner"
  gem "selenium-webdriver" # Call 'byebug' anywhere in the code to stop execution and get a debugger console
  gem 'pry-rails', '~> 0.3.4'
  gem 'pry-byebug', '3.1.0'
  gem 'awesome_print', '~> 1.6.1'
  gem 'spring'
end

group :development do
  # Better error pages for Rack Apps
  gem 'better_errors', '~> 2.1.1'
  # Enable the REPL and local/instance variable inspection
  gem 'binding_of_caller', '~> 0.7.2'
  # Control the launching of our local services
  gem 'foreman', '~> 0.78.0'
  # Automatically launches specs when files change
  gem 'guard-rspec', '~> 4.5.0'
  # Automatically reloads the browser when files change
  gem 'guard-livereload', '~> 2.4.0'
  # Injects livereload javascript into every request
  gem 'rack-livereload', '~> 0.3.15'
  # Turn off asset pipeline logging, it is loud
  gem 'quiet_assets', '~> 1.1.0'
  # Preview email in the browser instead of sending it.
  gem 'letter_opener', '~> 1.4.0'
  # Development tools for quality, style and security issues
  gem 'pronto', '~> 0.4.1'
  # Pronto runner for Rubocop, ruby code analyzer
  gem 'pronto-rubocop', '~> 0.4.3', require: false
  # Pronto runner for SCSS-Lint, tool to help keep your SCSS clean and readable
  gem 'pronto-scss', '~> 0.4.4', require: false
  # Pronto runner for Reek, code smell detector for Ruby
  gem 'pronto-reek', '~> 0.4.2', require: false
  # Pronto runner for Rails Best Practices, code metric tool for Rails projects
  gem 'pronto-rails_best_practices', '~> 0.4.0', require: false
  # Pronto runner for HAML-Lint, tool for writing clean and consistent HAML
  gem 'pronto-haml', '~> 0.4.3', require: false
  # Pronto runner for Flay, structural similarities analyzer
  gem 'pronto-flay', '~> 0.4.0', require: false
  # Pronto runner for Coffeelint, CoffeeScript code quality tool
  gem 'pronto-coffeelint', '~> 0.0.3', require: false
  # Pronto runer for Brakeman, security vulnerability scanner for RoR
  gem 'pronto-brakeman', '~> 0.4.0', require: false
  # Analyze code for potentially uncalled / dead methods
  gem 'sandi_meter', '~> 1.2.0', require: false
  # Analyze code for potentially uncalled / dead methods
  gem 'debride', '~> 1.1.0', require: false
  # Reports the most tortured code in an easy to read pain report
  gem 'flog', '~> 4.3.2'
end
