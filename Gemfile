source 'http://gems.vc.datys.cu'

gem 'rails', '3.2.13'

# Database
gem 'sqlite3'
#git 'https://github.com/matthuhiggins/foreigner.git' do
#  gem 'foreigner'
#end


# Authentication
gem "devise", ">= 2.2.3"

# AR enumerations
gem 'enumerize'

# Authorization
gem 'six'

# Background jobs processing
gem 'slim'
gem 'sinatra', :require => nil
gem 'sidekiq', '2.8.0'

# Application launching
gem 'foreman', '0.61.0'

# Scheduling
gem 'whenever', :require => false

# Settings/Configuration
gem 'settingslogic'

# Format dates
gem 'stamp'

# Colored output to console
gem 'colored'

# Log rotate
gem 'lograge'

# Form helpers
gem 'simple_form'


# UI components
gem "chosen-rails", "0.9.11.2"

# HAML
gem 'haml-rails'

# Database seeds
gem 'seed-fu', '~> 2.2.0'

### GROUPS ###
group :assets do
  # CSS related
  gem 'sass-rails', '~> 3.2.3'
  gem 'compass_twitter_bootstrap', :path => 'lib/compass-twitter-bootstrap'
  gem 'compass-rails' , '1.0.3'


  # Javascript related
  gem 'coffee-rails', '~> 3.2.1'
  gem "jquery-rails"
  gem 'jquery-ui-rails', '4.0.2'

  # Compression
  gem 'uglifier', '>= 1.0.3'
end


group :test do
  # Cucumber tests
  gem 'cucumber'
  gem "cucumber-rails", :require => false
  gem "capybara", ">= 2.0.3"
  gem "launchy", ">= 2.2.0"
  gem "database_cleaner", ">= 1.0.0.RC1"
  gem "haml", "4.0.0"

  # Test coverage
  gem "simplecov", :require => false

  # AR validation testing
  gem "shoulda-matchers", "2.1.0"
  # to understand rspec output in ci environment
  gem 'ci_reporter'

  # Metrics
  gem "brakeman", ">= 1.9.3"
end

group :development do
  # Preloading environment
  gem "spork"
  gem 'rails_best_practices'
  gem 'guard'
  gem 'guard-rails_best_practices'
  gem "guard-spork"
  gem "guard-bundler", ">= 1.0.0"
  gem "guard-cucumber", ">= 1.4.0"
  gem 'guard-migrate'
  gem "guard-rails", ">= 0.4.0"
  gem "guard-rspec", ">= 2.5.2"
  gem "rb-inotify", ">= 0.9.0", :require => false
  gem "rb-fsevent", ">= 0.9.3", :require => false
  gem "rb-fchange", ">= 0.0.6", :require => false
  gem 'wdm', :platforms => [:mswin, :mingw], :require => false
  gem 'libnotify' if /linux/ =~ RUBY_PLATFORM
  gem 'rb-notifu', :platforms => [:mswin, :mingw]
  gem 'win32console', :platforms => [:mswin, :mingw]
  gem 'win32-process', :platforms => [:mswin, :mingw]
  gem 'wdm', :platforms => [:mswin, :mingw]
  gem 'thin'
  # Assets
  gem "quiet_assets", ">= 1.0.2"

  # Better error display
  gem "better_errors", ">= 0.7.2"
  gem "binding_of_caller", ">= 0.7.1", :platforms => [:ruby]

  # Active redirect_to :controller => ""ord bottle neck tracker
  gem 'bullet'

  # Db Index discovery
  gem 'lol_dba'

  # Development tweaks
  gem 'rails-dev-tweaks', '~> 0.6.1'
end

group :production do
  # App server
  #gem 'puma', '~> 2.0.1', :platforms => [:ruby]
end

### GROUPS Mixed ###
group :test, :development do
  gem 'konacha'
  
  # Rspec
  gem "rspec-rails", ">= 2.12.2"

  # Testing factory
  gem "factory_girl_rails", ">= 4.2.0"

  # Error notification
  gem "airbrake", "3.1.12", :group => [:development, :test]

  # Configuration
  gem 'dotenv-rails', :groups => [:development, :test]
end
