source 'https://rubygems.org'
ruby '2.2.0'
#ruby-gemset=railstutorial_rails_4_0

gem 'rails', '4.2.3'
gem 'bootstrap-sass'
gem 'sprockets'
gem 'bcrypt-ruby'

group :development, :test do
  gem 'sqlite3', '1.3.10'
  gem 'rspec-rails', '3.3.2'
  gem 'rspec-its'
end

group :test do
  gem 'selenium-webdriver', '2.46.2'
  gem 'capybara', '2.2.0'
  gem 'factory_girl_rails', '4.2.1'
  gem 'cucumber-rails', '1.4.0', :require => false
  gem 'database_cleaner', github: 'bmabey/database_cleaner'
end

gem 'sass-rails', '4.0.5'
gem 'uglifier', '2.7.1'
gem 'coffee-rails', '4.1.0'
gem 'jquery-rails', '3.0.4'
gem 'turbolinks', '2.5.3'
gem 'jbuilder', '1.0.2'

group :doc do
  gem 'sdoc', '0.3.20', require: false
end

group :production do
  gem 'pg', '0.15.1'
  gem 'rails_12factor', '0.0.2'
end