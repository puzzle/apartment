# frozen_string_literal: true

source 'http://rubygems.org'

gem 'rails'

platforms :ruby do
  gem "sqlite3"
end

platforms :jruby do
  gem "activerecord-jdbc-adapter"
  gem "activerecord-jdbcpostgresql-adapter"
  gem "activerecord-jdbcmysql-adapter"
end

gemspec
