# frozen_string_literal: true

source 'https://rubygems.org'

git_source(:github) do |repo_name|
  repo_name = "#{repo_name}/#{repo_name}" unless repo_name.include?('/')
  "https://github.com/#{repo_name}.git"
end

gem 'coffee-rails'
gem 'hamlit-rails'
gem 'jbuilder'
gem 'pg'
gem 'puma'
gem 'rails'
gem 'sass-rails'
gem 'uglifier'

group :development, :test do
  gem 'factory_bot_rails'
  gem 'faker'
  gem 'haml-lint'
  gem 'pry-meta'
  gem 'rspec-rails'
  gem 'rubocop'
end

group :test do
  gem 'shoulda-matchers'
  gem 'simplecov'
end

group :development do
  gem 'listen', '>= 3.0.5', '< 3.2'
  gem 'spring'
  gem 'spring-watcher-listen', '~> 2.0.0'
  gem 'web-console', '>= 3.3.0'
end
