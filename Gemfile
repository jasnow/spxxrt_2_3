source "https://rubygems.org"

gem "rails", "7.0.7"

ruby File.read(".ruby-version")

gem "turbolinks"
gem "terser"
gem "jquery-rails"
gem "jbuilder"
gem "overcommit"
gem "rails-html-sanitizer"
gem "sassc-rails"
gem "sprockets-rails"
gem 'webrick'

gem "sdoc", group: :doc

group :development do
  gem "web-console"
  gem "ruby_audit"
  gem "spektr"
end

group :development, :test do
  gem "sqlite3"
  gem "spring"
  gem "brakeman"
  gem "standard"
  gem 'simplecov'
end

group :test do
  gem "minitest-reporters"
  gem "mini_backtrace"
  gem "guard-minitest"
  gem "guard"
end

group :production do
  # HID  gem 'pg' # HID on 10/3/2020
  gem "rails_12factor"
end
