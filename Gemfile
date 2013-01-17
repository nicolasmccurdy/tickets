source 'https://rubygems.org'

# Important stuff
gem 'rails', '~> 3.2'
gem 'thin'

# Database
group :production do
	gem 'pg'
end
group :development, :test do
	gem 'sqlite3'
end

# Gems used only for assets and not required
# in production environments by default.
group :assets do
	gem 'sass-rails',   '~> 3.2'
	gem 'bootstrap-sass', '~> 2.2'
	gem 'bootswatch-rails', '~> 0.3'
	gem 'font-awesome-sass-rails', '~> 3.0'
	gem 'coffee-rails', '~> 3.2'

	# See https://github.com/sstephenson/execjs#readme for more supported runtimes
	# gem 'therubyracer', :platforms => :ruby

	gem 'uglifier', '~> 1.0'
end

group :test do
	gem 'simplecov', require: false
end

group :development do
	gem 'binding_of_caller'
	gem 'better_errors'
end

gem 'jquery-rails'
gem 'browser_details'

# To use ActiveModel has_secure_password
# gem 'bcrypt-ruby', '~> 3.0'

# To use Jbuilder templates for JSON
# gem 'jbuilder'

# Use unicorn as the app server
# gem 'unicorn'

# Deploy with Capistrano
# gem 'capistrano'

# To use debugger
# gem 'debugger'
