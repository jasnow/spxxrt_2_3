source 'https://rubygems.org'

# Rails 5.0
gem 'rails'     , git: 'git://github.com/rails/rails.git'
gem 'arel'      , git: 'git://github.com/rails/arel.git'
gem 'rack'      , git: 'git://github.com/rack/rack.git'
gem 'turbolinks', git: 'git://github.com/rails/turbolinks.git' # Needed to fix dep warnings.

ruby '2.2.3'

gem 'uglifier'
gem 'coffee-rails'
gem 'jquery-rails'
gem 'jbuilder'
gem 'overcommit'
gem 'rails-html-sanitizer'
gem 'sass-rails'
gem 'sdoc', group: :doc
gem 'sprockets'
gem 'sprockets-rails'

group :development do
  gem 'web-console'
end

group :development, :test do
  gem 'sqlite3'
  gem 'byebug'
  gem 'spring'
end

group :test do
  gem 'minitest-reporters'
  gem 'mini_backtrace'
  gem 'guard-minitest'
  gem 'guard'
end

group :production do
  gem 'pg'
  gem 'rails_12factor'
end
