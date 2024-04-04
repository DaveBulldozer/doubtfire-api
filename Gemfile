source 'https://rubygems.org'

# Ruby versions for various enviornments
ruby_versions = {
  development: '~>3.1.0',
  test: '~>3.1.0',
  staging: '~>3.1.0',
  production: '~>3.1.0'
}
# Get the ruby version for the current enviornment
ruby ruby_versions[(ENV['RAILS_ENV'] || 'development').to_sym]

# The venerable, almighty Rails
gem 'rails', '~> 7.0', '>= 7.0.8.1'

group :development, :test do
  gem 'better_errors', '>= 2.10.0'
  gem 'byebug'
  gem 'database_cleaner'
  gem 'listen'
  gem 'rails_best_practices'
  gem 'rubocop'
  gem 'rubocop-faker'
  gem 'rubocop-rails', '>= 2.19.0'
  gem 'simplecov', require: false
  gem 'solargraph', '>= 0.49.0', require: false
  gem "sprockets-rails"
end

group :development, :test, :staging do
  # Generators for population
  gem 'factory_bot'
  gem 'factory_bot_rails', '>= 6.3.0'
  gem 'faker'
  gem 'minitest'
  gem 'minitest-around'
  gem 'webmock'
end

# Database
gem 'mysql2'

# Webserver - included in development and test and optionally in production
gem 'puma'

gem 'bootsnap', require: false

# Extend irb for better output
gem 'hirb'

# Authentication
gem 'devise', '>= 4.9.1'
gem 'devise_ldap_authenticatable'
gem 'json-jwt'
gem 'ruby-saml', '~> 1.14.0'

# Student submission
gem 'coderay'
gem 'rmagick'
gem 'ruby-filemagic'
gem 'rubyzip'

# Plagarism detection
gem 'moss_ruby', '>= 1.1.4'

# Latex
gem 'rails-latex', '>= 2.3.4'

# API
gem 'grape', '>= 1.7.1'
gem 'grape-entity'
gem 'grape-swagger', '>= 1.6.0'
gem 'grape-swagger-rails', '>= 0.4.0'

# Miscellaneous
gem 'bunny-pub-sub', '0.5.2'
gem 'ci_reporter'
gem 'dotenv-rails', '>= 3.0.0'
gem 'rack-cors', '>= 2.0.1', require: 'rack/cors'
gem 'require_all', '>=1.3.3'

# Excel support
gem 'roo', '~> 2.8.0'
gem 'roo-xls'

# webcal generation
gem 'icalendar'

gem 'rest-client'

gem 'net-smtp', require: false
