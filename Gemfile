# -*- ruby -*-

source 'http://rubygems.org'

gem 'rails'
gem 'rack-contrib'
gem 'SystemTimer'

# ActiveRecord requires a database adapter.
gem 'pg'
gem 'mongo_mapper'
gem 'bson_ext'

# Bulk data importing
gem 'activerecord-import'

# Rails.cache
gem 'memcache-client'
# gem 'memcached'

# Configuration/deploy management
gem 'settingslogic'
gem 'capistrano'
gem 'capistrano-ext'
gem 'whenever', :require => false

# An alternative form builder
gem 'formtastic', '~> 1.1.0'

# Authentication
gem 'devise'
gem 'ruby_parser'

# GIS & Geocoding
gem 'GeoRuby'
gem 'geokit'
gem 'geoip'

# Breadcrumbs & navigation
gem 'simple-navigation'

# Static pages
gem 'high_voltage'

# Background tasks
gem 'delayed_job', '~> 2.1'

# Attachments & assets
gem 'paperclip'
gem 'jammit'
gem 'docsplit'

# Views & Javascript
gem 'haml'
gem 'jquery-rails'

# Tagging
gem "acts-as-taggable-on", :git => 'http://github.com/mbleigh/acts-as-taggable-on.git'

# Importing & parsing stuff
gem 'httparty'
gem 'nokogiri'
gem 'chronic' # Complex date string parsing
gem 'json'
gem 'fastercsv'
# gem 'govkit', :git => 'git://github.com/opengovernment/govkit.git' (SUBMODULE)

# Indexing and Search
gem 'thinking-sphinx', '~> 2.0.3'

# Pagination
gem 'kaminari'

# Graphics
gem 'googlecharts', '~> 1.6.1', :require => 'gchart'

# Logging
gem 'hoptoad_notifier'
gem 'SyslogLogger'

group :development do
  gem 'silent-postgres'	# Quieter postgres log messages
  gem 'rails_complete'	# Rails console tab completion; see https://github.com/dasch/rails-complete for install instructions
  gem 'hirb'
  gem 'awesome_print'
end

# Bundle gems used only in certain environments:
group :test do
  # Bundle gems for certain environments:
  gem 'database_cleaner'
  gem 'launchy'    # So you can do "Then show me the page"
  gem 'rspec-rails', '>= 2.0.0.rc'
  gem 'spork'
  gem 'capybara', '~> 0.4.1'
  gem 'cucumber', '~> 0.10.0'
  gem 'cucumber-rails', '~> 0.3.2'
  gem 'autotest'
  gem 'autotest-rails'
  gem 'factory_girl_rails'
  gem 'linecache'
  gem 'ruby-debug'
  gem 'vcr', '~> 1.5.1'
  gem 'fakeweb', '~> 1.3.0'
end
