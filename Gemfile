source "https://rubygems.org"
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby "3.2.2"

gem "administrate", "~> 0.17.0"
gem "bcrypt"
gem "bootsnap", require: false
gem "discard", "~> 1.2"
gem "jbuilder"
gem "jwt"
gem "mysql2", "~> 0.5"
gem "omniauth-cognito-idp"
gem "omniauth-rails_csrf_protection"
# gem "peraichi_common", github: "HotStartup/peraichi-common-rails", tag: "v0.3.0"
gem "puma", "~> 5.0"

gem "rack-cors"
gem "rails", "~> 7.0.4", ">= 7.0.4.3"
gem "rails-i18n"
gem "sentry-rails"
gem "sentry-ruby"
gem "sprockets-rails"
gem "tzinfo-data", platforms: %i[ mingw mswin x64_mingw jruby ]

##############
# # Use JavaScript with ESM import maps [https://github.com/rails/importmap-rails]
gem "importmap-rails"

group :development, :test do
  gem "bundler-audit"
  gem "debug", platforms: %i[ mri mingw x64_mingw ]
  gem "rspec-rails"
end

group :development do
  gem "annotate"
  gem "rubocop"
  gem "rubocop-github"
  gem "rubocop-rails"
  gem "rubocop-rspec"
  gem "web-console"
end

group :test do
  gem "capybara"
  gem "factory_bot_rails"
  gem "rspec_junit_formatter"
  gem "selenium-webdriver"
  gem "simplecov", require: false
  gem "sinatra"
  gem "webmock"
end