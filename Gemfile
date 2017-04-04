source 'https://rubygems.org'
ruby '~> 2.2.6'

# Bundler 1.x default to insecure http:// for github: shortcut
git_source(:github){ |repo_name| "git@github.com:#{repo_name}.git" }

gem 'rails', '~> 4.2.7'
gem 'rake', '< 11.0' # until we upgrade to rspec 3

gem 'mysql2', '~> 0.4.5' # for user database
gem 'pg'

gem 'newrelic_rpm', '~> 3.18'

# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
gem 'jbuilder', '~> 1.2'

# Use unicorn as the app server
gem 'unicorn'

gem 'api_hammer', '~> 0.16.0'
gem 'lograge'

gem 'kaminari'
gem 'uuidtools'
gem 'faraday'

gem 'venuenext_rails_config', github: 'venuenext/venuenext_rails_config', tag: 'v0.3.4'
gem 'notify_client', github: 'venuenext/notify_client', tag: 'v0.1.8'
gem 'venuenext_oauth_config', github: 'venuenext/venuenext_oauth_config', tag: 'v1.11.2' # v1.11.3 has breaking changes
gem 'pony_express', github: 'venuenext/pony_express', tag: 'v0.3.3'
gem 'venuenext_es_record', github: 'venuenext/venuenext_es_record', tag: 'v0.1.3'
gem 'venuenext_s3_tools', github: 'venuenext/venuenext_s3_tools', tag: 'v1.0'

gem 'redis', '~> 3.1.0'
gem 'redis-namespace'
gem 'redis-rails', '~> 4.0.0'
gem 'redis-rack-cache', '~> 1.2.2'

gem 'sidekiq', '~> 3.1.3'
gem 'sidekiq-failures'
gem 'sinatra', '>= 1.3.0', :require => nil # if you require 'sinatra' you get the DSL extended to Object


gem 'rollbar'
gem 'oj'

gem 'hashie'

group :test, :development do
  gem 'looksee'
  gem 'coveralls', :require => false
  gem 'webmock', '< 2', :require => false
  gem 'timecop'
  gem 'vcr'
  gem 'json_spec'
  gem 'byebug'
  gem 'rspec-rails', '~> 2.99'
  gem 'cucumber-rails', :require => false
  gem 'cuke-step-bm'
  gem 'database_cleaner'
  gem 'pickle'
  gem 'waterfront', github: 'venuenext/waterfront', tag: 'v1.0.12'
  gem 'capybara'
  gem 'factory_girl_rails', "~> 4.0"
  gem 'shoulda-matchers'
end
