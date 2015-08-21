source 'https://rubygems.org'

# Rails 5.0
gem 'rails',       git: 'git://github.com/rails/rails.git'
gem 'arel',        git: 'git://github.com/rails/arel.git'
gem 'turbolinks',  git: 'git://github.com/rails/turbolinks.git'
gem 'rack'

ruby '2.2.3'

gem 'sass-rails'
gem 'uglifier'
gem 'coffee-rails'
gem 'jquery-rails'
gem 'jbuilder'
gem 'rails-html-sanitizer'
gem 'sdoc', group: :doc
gem 'overcommit'

group :development do
  # Needed for Rails 5.0
  gem 'web-console', git: 'git://github.com/rails/web-console.git'
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
