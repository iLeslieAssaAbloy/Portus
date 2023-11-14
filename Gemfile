# frozen_string_literal: true

source "https://rubygems.org"

gem "active_record_union"
gem "base32"
gem "devise", ">= 4.7.0"
gem "font-awesome-rails", ">= 4.7.0.6"
gem "grape"
gem "grape-entity"
gem "grape-swagger"
gem "grape-swagger-entity"
gem "gravatar_image_tag"
gem "hashie-forbidden_attributes"
gem "jwt"
gem "kaminari", ">= 1.2.0"
gem "net-ldap"
gem "omniauth-github", ">= 2.0.0"
gem "omniauth-gitlab", ">= 3.0.0"
gem "omniauth-google-oauth2", ">= 0.7.0"
gem "omniauth-openid", ">= 2.0.1"
gem "omniauth_openid_connect", ">= 0.4.0"
gem "public_activity", "~> 1.6.4"
gem "pundit"
gem "rails", "~> 5.2.4"
gem "redcarpet", ">= 3.5.1"
gem "sassc-rails", ">= 2.1.1"
gem "search_cop"
gem "slim"
gem "webpack-rails"

gem "rack-cors", ">= 1.0.5"

# Supported DBs
gem "mysql2", group: :db
gem "pg", group: :db

# Pinning these specific versions because that's what we have on OBS.
gem "ethon"
gem "typhoeus"

# Used to store application tokens.
gem "bcrypt"

# If the deployment is done through Puma, include it in the bundle.
gem "puma", ">= 5.6.7"

# Configuration management
gem "cconfig", "~> 1.2.0"

# Pinning some versions
gem "i18n"
gem "ice_nine"
gem "minitest"
gem "multi_json"
gem "rails-dom-testing", ">= 2.1.0"
gem "sprockets"
gem "sprockets-rails", ">= 3.2.2"
gem "temple"

##
# The following groups will *not* be included on the production installation.

group :assets do
  gem "bootstrap-sass"
  gem "uglifier"
end

group :development do
  gem "annotate"
  gem "git-review", require: false
  gem "guard", require: false
  gem "guard-rspec", require: false
  gem "guard-rubocop", require: false
  gem "pry-rails"
  gem "rack-mini-profiler", require: false
  gem "rails-erd"
  gem "web-console", ">= 4.0.0"
end

group :development, :test do
  gem "rspec-core"
  gem "rspec-rails", ">= 3.8.3"

  gem "awesome_print"
  gem "binman"
  gem "brakeman", require: false
  gem "byebug"
  gem "database_cleaner"
  gem "factory_bot_rails", ">= 5.1.0"
  gem "ffaker"
  gem "grape-swagger-rails", ">= 0.4.0"
  gem "hirb"
  gem "rubocop", require: false
  gem "wirb"
  gem "wirble"
end

group :test do
  gem "capybara", ">= 3.14.0"
  gem "capybara-screenshot", ">= 1.0.23"
  gem "chromedriver-helper"
  gem "docker-api", ">= 2.0.0"
  gem "json-schema"
  gem "poltergeist", require: false
  gem "rails-controller-testing", ">= 1.0.5"
  gem "selenium-webdriver", ">= 3.142.0"
  gem "shoulda"
  gem "simplecov", ">= 0.17.0", require: false
  gem "timecop"
  gem "vcr"
  gem "webmock", require: false
end
