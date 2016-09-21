source 'https://rubygems.org'

gem 'sinatra', '~> 1.4.7'
gem 'sinatra-contrib'
gem 'unicorn'
gem 'json'
gem 'colorize'
gem 'yajl-ruby'
gem "rest-client"
gem 'rake'
gem 'mixlib-versioning', '~> 1.1.0'
# Update to mixlib-install 2.0.0 when released!
gem 'mixlib-install', :git => 'https://github.com/chef/mixlib-install.git', :branch => 'pw/package-router'
gem 'trashed'

group :test do
  gem 'rspec'
  gem 'rspec-legacy_formatters'
  gem 'rspec-rerun', '~> 0.3.0'
  gem 'rspec-its'
  gem 'rack-test'
  gem 'rspec_junit_formatter'
end

group :security do
  gem 'bundler-audit'
end
