source 'https://rubygems.org'

ruby '2.2.4'

gem 'rails', '5.0.1'

# Web server
gem 'puma'
gem 'foreman'

# Database
gem 'mysql2'

# Asset managments
gem 'turbolinks'
gem 'sass-rails', '~> 5.0'
gem 'uglifier', '>= 1.3.0'
gem 'coffee-rails', '~> 4.1.0'
gem 'jquery-rails'
gem 'react-rails'
gem 'lodash-rails'
gem 'momentjs-rails'
gem 'materialize-sass'
gem 'font-awesome-sass', '~> 4.6.2'

# Serializer
gem 'jbuilder', '~> 2.0'

# Authentications
gem 'devise'
gem 'devise_invitable'

# Phone handling / validation
gem 'phony_rails'

# Upload Handler
gem 'carrierwave'

# Custom error message
gem 'custom_error_message'

# PDF generation
gem 'wicked_pdf'
gem 'wkhtmltopdf-binary'

# Exception notification
gem 'exception_notification'
gem 'slack-notifier'

# Handling sms message
gem 'twilio'
gem 'twilio-ruby', '~> 4.11.1'

# Others
gem 'rake', '12.0.0'
gem 'config'

group :doc do
  gem 'sdoc', '~> 0.4.0'
end

group :development, :test do
  gem 'pry'
  gem 'rspec-rails'
  gem 'factory_girl_rails', '~> 4.0'
  gem 'rubocop'
  gem "rails_best_practices"
end

group :development do
  # Access an IRB console on exception pages or by using <%= console %> in views
  gem 'web-console', '~> 2.0'
  gem 'capistrano-rails'
  gem 'annotate'
  # Windows does not include zoneinfo files, so bundle the tzinfo-data gem
  gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]
end

group :test do
  gem 'database_cleaner'
end

group :production do
 gem 'libv8', '~> 3.16.14.17'
 gem 'therubyracer', :platform => :ruby
end
