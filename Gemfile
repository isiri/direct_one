source 'http://rubygems.org'

gem 'rails', '3.1.3'

# Bundle edge Rails instead:
# gem 'rails',     :git => 'git://github.com/rails/rails.git'

gem 'mysql2'
gem 'twitter-bootstrap-rails'

# Gems used only for assets and not required
# in production environments by default.
group :assets do
  gem 'sass-rails',   '~> 3.1.4'
  gem 'coffee-rails', '~> 3.1.1'
  gem 'uglifier', '>= 1.0.3'
end

gem 'jquery-rails'

gem 'haml', '>= 3.1.2'
gem 'jquery-rails'
gem "devise", ">= 1.4.9"

#For Rails 3.1, a JavaScript runtime is needed for Linux Ubuntu. It is not needed for Mac OS X or Windows.
gem 'execjs'
gem 'therubyracer'
 
gem 'haml-rails', '>= 0.3.4', :group => [:development]

#these are for heroku can be removed latter
group :production do
  gem 'therubyracer-heroku', '0.8.1.pre3' # you will need this too
  gem 'pg'
end
# To use ActiveModel has_secure_password
# gem 'bcrypt-ruby', '~> 3.0.0'

# Use unicorn as the web server
# gem 'unicorn'

# Deploy with Capistrano
# gem 'capistrano'

# To use debugger
# gem 'ruby-debug19', :require => 'ruby-debug'

group :test do
  # Pretty printed test output
  gem 'spork', "~> 0.8.5"
  gem 'spork-testunit', "~> 0.0.7"
  gem 'factory_girl'
  gem 'capybara', "~> 1.1.2"
  gem 'capybara_minitest_spec' #MiniTest expectations for Capybara — Read more
  gem 'database_cleaner'
  gem 'minitest', "~> 2.9.1"
  gem 'turn', :require => false
end
