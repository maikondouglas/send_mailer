source 'https://rubygems.org'
git_source(:github) { |repo| 'https://github.com/#{repo}.git' }

ruby '3.2.0'

gem 'rails', '~> 7.0.5'
gem 'sqlite3', '~> 1.4'
gem 'puma', '~> 5.0'
gem 'tzinfo-data', platforms: %i[ mingw mswin x64_mingw jruby ]
gem 'bootsnap', require: false
gem 'rack-cors'
gem 'mailcatcher'

group :development, :test do
  gem 'byebug'
  gem 'rspec-rails', '~> 6.0'
  gem 'faker'
  gem 'spring-commands-rspec'
  gem 'factory_bot_rails'
  gem 'shoulda-matchers'
  gem 'rubocop', require: false
  gem 'rubocop-factory_bot', require: false
  gem 'rubocop-rails', require: false
  gem 'rubocop-rspec', require: false
  gem 'dotenv-rails'
end

group :test do
  gem 'simplecov', require: false
end
