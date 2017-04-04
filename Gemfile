source 'https://rubygems.org'

ruby '~> 2.2.5'
gem 'rails', '~> 4.1.15'
gem 'venuenext_rails_config', git: 'git@github.com:venuenext/venuenext_rails_config.git', tag: 'v0.3.4'

gem 'rack'

gem 'oauth2'

gem 'addressable', :require => ['addressable/uri', 'addressable/template']
gem 'haml'
gem 'haml-rails'
gem 'kaminari', '~> 0.15.1'
gem 'elasticsearch', '~> 1.0'
gem 'redis', '~> 3.2.0'
gem 'redis-namespace', '~> 1.5.0'
gem 'redis-rails', '~> 4.0.0'
gem 'redis-rack-cache', '~> 1.2.2'
gem 'sidekiq', '~> 4.2.3'
gem 'sidekiq-failures'
gem 'sinatra', '>= 1.3.0', :require => nil
gem 'mysql2', '~> 0.3.0'
gem 'nokogiri', '~> 1.6.2.1'
gem 'api_hammer', '~> 0.14.1'
gem 'lograge', '~> 0.3.0'
gem 'venuenext_oauth_config', :git => 'git@github.com:venuenext/venuenext_oauth_config.git', :tag => 'v1.10.1'
gem 'venuenext_notifications', :git => 'git@github.com:venuenext/venuenext_notifications', :tag => 'v1.0.11'
gem 'carrierwave'
gem 'whenever', '~>0.9.2', :require => false
gem 'rack-pjax'
gem 'pony_express', :git => 'git@github.com:venuenext/pony_express.git', :tag => 'v0.2.5'
gem 'jimi_express', :git => 'git@github.com:venuenext/jimi_express.git', :tag => 'v0.0.2'
gem 'venuenext_payments', :git => 'git@github.com:venuenext/venuenext_payments.git', :tag => 'v0.7.5'
gem 'venue_client', :git => 'git@github.com:venuenext/venue_client.git', :tag => "v0.3.4"
gem 'notify_client', :git => 'git@github.com:venuenext/notify_client.git', :tag => 'v0.1.9'
gem 'venuenext_s3_tools', git: 'git@github.com:venuenext/venuenext_s3_tools.git', :tag => 'v1.1'
gem 'venuenext_es_record', git: 'git@github.com:venuenext/venuenext_es_record.git', tag: 'v0.1.2'

gem 'remotipart', '~> 1.2'
gem "jquery-fileupload-rails"
gem 'dimensions'
gem 'state_machine'
gem 'handlebars_assets', '~> 0.20.1'
gem 'jquery-tablesorter'
gem 'mandrill_mailer', '~>0.4.5'
gem 'mandrill-api'
gem 'react-rails'
gem 'react-rails-hot-loader'

gem "browserify-rails"

gem 'rails-observers'

# Use Uglifier as compressor for JavaScript assets
gem 'uglifier', '>= 1.3.0'
gem 'bootstrap-sass', '~> 3.3.6'
gem 'sass-rails', '>= 3.2'
gem 'bootstrap-sass-extras'
gem "autoprefixer-rails"

# Use CoffeeScript for .js.coffee assets and views
gem 'coffee-rails', '~> 4.0.0'

gem 'bootstrap-multiselect-rails'
gem 'bootstrap-select-rails'

#both required for datetimepicker
gem 'momentjs-rails', '>= 2.9.0'
gem 'bootstrap3-datetimepicker-rails', '~> 4.17.37'
gem 'bootstrap-switch-rails'

# See https://github.com/sstephenson/execjs#readme for more supported runtimes
gem 'therubyracer', platforms: :ruby


# Use jquery as the JavaScript library
gem 'jquery-rails'

# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
gem 'jbuilder', '~> 1.2'

gem 'newrelic_rpm'

gem 'faraday'
gem 'faraday_middleware'
gem 'curb'
gem 'hashie'

# Send errors to Rollbar
gem 'rollbar'
gem 'oj'

# Prevent deprecation warnings from v3.7.0 for now.
gem 'sprockets', '~> 3.6.3'

group :test, :development do
  gem "byebug", '< 4'
  gem 'pry-byebug'
  gem 'rspec-rails', '~> 3.4.0'
  gem 'looksee'
  gem 'annotate', :git => 'git@github.com:venuenext/annotate_models', :ref => 'fea8f6a8' # :branch => 'd_exclude_sti_subclasses'
  gem 'better_errors'
end

group :test do
  gem 'cucumber-rails', :require => false, group: [:test]
  gem 'cucumber', "~> 1.3.17"
  gem 'selenium-webdriver', "~> 2.47.0"
  gem 'poltergeist'
  gem 'vcr'
  gem 'database_cleaner'
  gem 'webmock'
  gem 'pickle'
  gem 'factory_girl_rails', "~> 4.0"
  gem 'json_spec', :git => "git@github.com:venuenext/json_spec.git", :require => false
  gem 'waterfront', :git => 'git@github.com:venuenext/waterfront.git', :tag => 'v1.0.9'
  gem 'cucumber-timecop', :require => false
  gem 'shoulda-matchers', "~> 2.5.0", require: false
  gem 'codecov', :require => false
end

group :development do
  gem 'binding_of_caller'
  gem 'guard'
  gem 'guard-rspec', require: false
end

# Use unicorn as the app server
gem 'unicorn'
