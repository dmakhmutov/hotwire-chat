# frozen_string_literal: true

source "https://rubygems.org"
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby "3.2.0"

gem "rails", "~> 7.0.4", ">= 7.0.4.2"
gem "sprockets-rails"

gem "importmap-rails"
gem "puma", "~> 5.0"
gem "sqlite3", "~> 1.4"
gem "stimulus-rails"
gem "tailwindcss-rails"
gem "turbo-rails"

gem "jbuilder"
gem "redis", "~> 4.0"

gem "bootsnap", require: false

# Use Sass to process CSS
gem "sassc-rails"
gem "slim", "= 3.0.9"
gem "slim-rails", "~> 3.2"

group :development, :test do
  gem "pry-nav", "~> 1.0"

  gem "rubocop", "~> 1.44", require: false
end

group :development do
  gem "rack-mini-profiler"
  gem "web-console"
end
