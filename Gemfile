# frozen_string_literal: true

source 'https://rubygems.org'

gem 'jruby-openssl', platforms: :jruby
gem 'rake', '~> 13.0', '>= 13.0.1'

group :development do
  gem 'awesome_print', require: 'ap'
  gem 'yard'
end

group :test do
  gem 'coveralls', :require => false
  gem 'json', '~> 1.7', :platforms => [:jruby]
  gem 'jwt', '~> 1.5', '>= 1.5.6'
  gem 'multi_json', '~> 1.11.0'
  gem 'mime-types', '< 2.0.0'
  gem 'netrc', '~> 0.7.7'
  gem 'rb-fsevent', '~> 0.9'
  gem 'rspec', '~> 3.0.0'
  gem 'simplecov', :require => false
  gem 'vcr', '~> 4.0'
  gem 'webmock', '~> 3.4', '>= 3.4.2'
  gem 'coveralls', require: false
  gem 'simplecov', require: false
end

group :test, :development do
  gem 'activesupport'
  gem 'oas_parser'
  gem 'redcarpet'
  gem 'pry-byebug'
end

platforms :rbx do
  gem 'psych'
  gem 'rubysl', '~> 2.0'
end

gemspec
