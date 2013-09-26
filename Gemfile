source 'http://gems.vc.datys.cu'

gem 'rails', '3.2.13'

gem 'active_presenter', '3.2.2'
gem 'responders', '0.9.3'


# Database
gem 'sqlite3', '1.3.8'

# json template api
gem 'rabl', '0.8.6'
#gem 'facets', '2.9.3'

# I18n database fields models
gem 'globalize3', '0.3.0'

# Authentication
gem 'devise', '3.1.0'

# Authorization
gem 'six', '0.2.0'

gem 'enumerize', '0.7.0' # AR enumerations

# Background jobs processing
##gem 'slim', '1.3.6'
##gem 'sinatra', '1.4.3', :require => nil
##gem 'sidekiq', '2.12.4'

# Application launching
gem 'foreman', :ref => 'http://gitlab.vc.datys.cu//external-apis/foreman.git' # (version 0.63.0)

##gem 'whenever', '0.8.2', :require => false # Scheduling

##gem 'settingslogic', '2.0.9' # Settings/Configuration

##gem 'stamp', '0.5.0' # Format dates

gem 'airbrake', '3.1.14' # Error notification

gem 'lograge', '0.2.0' # Log rotate

gem 'simple_form', '2.1.0' # Form helpers

# UI components
gem 'chosen-rails', '1.0.0'
gem 'pnotify-rails', '1.2.2'

# Views
gem 'haml-rails', '0.4'
gem 'haml', '4.0.3'

gem 'pjax_rails', '0.3.4'
gem 'kaminari', '0.14.1'


##gem 'seed-fu', '2.2.0'  # Database seeds

gem 'factory_girl_rails', '4.2.1'

# Active Record Nesting
gem 'awesome_nested_set', '2.1.6'
gem 'the_sortable_tree', '2.4.0'

group :assets do
  # CSS related
  gem 'sass-rails', '3.2.6'
  gem 'compass_twitter_bootstrap', '2.3.1'
  gem 'compass-rails' , '1.0.3'

  # Javascript related
  gem 'coffee-rails', '3.2.2'
  gem 'jquery-rails', '3.0.4'
  gem 'jquery-ui-rails', '4.0.4'

  # edit inline
  gem 'best_in_place'

  # Compression
  gem 'uglifier', '2.1.1'
end

group :test do
  gem 'cucumber', '1.3.7'
  gem 'cucumber-rails', '1.4.0', :require => false
  gem 'capybara', '2.1.0'
  gem 'launchy', '2.3.0'
  gem 'database_cleaner', '1.1.1'

  gem 'konacha', '3.0.0' # Javascript test with mocha framework

  gem 'simplecov', '0.7.1', :require => false  # Test coverage

  gem 'simplecov-rcov', '0.2.3', :require => false  # Test coverage


  gem 'shoulda-matchers', '2.2.0' # AR validation testing

  gem 'enumerize-matchers', '0.0.1' # Enumerize validation

  gem 'ci_reporter', '1.9.0' # to understand rspec output in ci environment

  # Metrics
  gem 'brakeman', '2.1.1'
  gem 'metric_fu', '4.4.1'

  gem 'capybara-webkit' if /linux/ =~ RUBY_PLATFORM
end

group :development do
  # Preloading environment
  gem 'spork', '0.9.2'
  gem 'rb-inotify', '0.9.1', :require => false
  gem 'rb-fsevent', '0.9.3', :require => false
  gem 'rb-fchange', '0.0.6', :require => false
  gem 'wdm', '0.1.0', :platforms => [:mswin, :mingw], :require => false
  gem 'libnotify' if /linux/ =~ RUBY_PLATFORM
  gem 'rb-notifu', '0.0.4', :platforms => [:mswin, :mingw]
  gem 'win32console', '1.3.2', :platforms => [:mswin, :mingw]
  gem 'win32-process', '0.7.2', :platforms => [:mswin, :mingw]

  # Better error display
  gem 'better_errors', '1.0.1'
  gem 'binding_of_caller', '0.7.1', :platforms => [:ruby]

  gem 'quiet_assets', '1.0.2' #Remove assets logs

  # Code quality
  gem 'bullet', '4.6.0' #Detect N+1 query and eager loading
  gem 'rails_best_practices', '1.14.3'
  gem 'lol_dba', '1.6.0' #Db Index discovery

   # misc
  gem 'rails-dev-tweaks', '0.6.1'  #tweaks to improve your Rails (3.1+) development experience.
  gem 'colored', '1.2'  # Colored output to console

  gem 'annotate', '2.5.0'
end

group :production do
  gem 'puma', '2.5.1', :platforms => [:ruby] # App server
end

group :test, :development do
  gem 'rspec-rails', '2.13.0'

  gem 'dotenv-rails', '0.9.0' # Configuration

  # RSpec matchers and Cucumber steps for testing JSON content
  gem 'json_spec', '1.1.1'
end

gem 'gon', '4.1.0'

gem 'amcharts-rails', :ref => 'http://gitlab.vc.datys.cu//external-apis/amcharts-rails.git'

gem 'beesor-jquery-render-rails', :git => 'git@gitlab.vc.datys.cu:apis/beesor-jquery-render-rails.git'
