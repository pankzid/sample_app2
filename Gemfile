source 'https://rubygems.org'

gem 'rails', '3.2.14'

# Bundle edge Rails instead:
# gem 'rails', :git => 'git://github.com/rails/rails.git'

group :development, :test do
	gem 'sqlite3'
	gem 'rspec-rails', '2.14.0'
	gem 'guard-rspec', '3.0.2'
	gem 'guard-spork', '1.5.1'
	gem 'childprocess', '0.3.9'
	gem 'spork', '0.9.2'
end


# Gems used only for assets and not required
# in production environments by default.
group :assets do
  gem 'sass-rails',   '~> 3.2.5'
  gem 'coffee-rails', '~> 3.2.2'
  gem 'uglifier', '>= 1.2.3'

  # See https://github.com/sstephenson/execjs#readme for more supported runtimes
  # gem 'therubyracer', :platforms => :ruby

end

gem 'jquery-rails', '2.0.2'

group :test do
	gem 'capybara', '1.1.2'
	gem 'rb-fchange', '0.0.5'
	gem 'rb-notifu', '0.0.4'
	gem 'win32console', '1.3.0'
end

group :production do
	gem 'pg', '0.12.2'
end

#asr for guard
require 'rbconfig'
gem 'wdm', '>= 0.1.0' if RbConfig::CONFIG['target_os'] =~ /mswin|mingw/i
# To use ActiveModel has_secure_password
# gem 'bcrypt-ruby', '~> 3.0.0'

# To use Jbuilder templates for JSON
# gem 'jbuilder'

# Use unicorn as the app server
# gem 'unicorn'

# Deploy with Capistrano
# gem 'capistrano'

# To use debugger
# gem 'debugger'
