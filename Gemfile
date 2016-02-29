source 'https://rubygems.org'

ruby '2.2.3' # stop Heroku complaining

gem 'rails', '4.2.4'
gem 'rails-api'
gem 'pg'
gem 'bower-rails'
gem 'sass'
gem 'devise_token_auth'
gem 'omniauth'
gem 'sqlite3' # don't really want this, but rspec is calling for it

group :production do
  gem "rails_12factor"
end

group :development do
  gem 'spring'
end

group :test, :development do
  gem 'rspec-rails'
  gem 'factory_girl_rails'
  gem 'capybara'
  gem "database_cleaner"
  gem "selenium-webdriver"
end

group :test do
  gem 'faker'
end
