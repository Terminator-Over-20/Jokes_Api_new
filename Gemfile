source 'https://rubygems.org'
gem 'sinatra'
gem 'data_mapper'

group :development do
  gem 'sqlite3', '~> 1.3', '< 1.4'
  gem "dm-sqlite-adapter"
end

group :production do
  gem 'pg'
  gem 'dm-postgres-adapter'
end