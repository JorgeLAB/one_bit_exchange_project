source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby '2.6.5'

#Basic
gem 'rails', '~> 6.0.2', '>= 6.0.2.2'

gem 'pg', '>= 0.18', '< 2.0'

gem 'puma', '~> 4.1'

gem 'sass-rails', '>= 6'
gem 'haml'
gem "haml-rails", "~> 2.0"

gem 'webpacker', '~> 4.0'

gem 'turbolinks', '~> 5'
gem 'jbuilder', '~> 2.7'

gem 'bootsnap', '>= 1.4.2', require: false

gem 'rest-client'

group :development, :test, :production do
  gem 'byebug', platforms: [:mri, :mingw, :x64_mingw]
  gem 'rspec-rails', '~> 4.0'
  gem 'dotenv-rails'
end



group :development do
  gem 'web-console', '>= 3.3.0'
  gem 'listen', '>= 3.0.5', '< 3.2'
  gem 'spring'
  gem 'spring-watcher-listen', '~> 2.0.0'
  gem 'better_errors'
  gem "binding_of_caller"
end

group :test do
  gem 'capybara', '>= 2.15'
  gem 'selenium-webdriver'
  gem 'webdrivers'
end

gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]

gem 'rubocop', require: false

gem 'rubocop-rails', require: false
