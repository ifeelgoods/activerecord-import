source 'https://rubygems.org'

gem "activerecord", "~> 3.0"

group :development do
  gem "rake"
  gem "jeweler", ">= 1.4.0"
end

group :test do
  # Database Adapters
  platforms :ruby do
    gem "mysql", "~> 2.8.1"
    gem "mysql2", "~> 0.3.0"
    gem "sqlite3-ruby", "~> 1.3.1"
  end

  platforms :jruby do
    gem "jdbc-mysql"
    gem "activerecord-jdbcmysql-adapter"
  end

  # Support libs
  gem "factory_girl", "~> 1.3.3"
  gem "delorean", "~> 0.2.0"

end
