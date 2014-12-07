source 'https://rubygems.org'

# Specify your gem's dependencies in compass-rails.gemspec
gemspec

group :assets do
  gem "compass", '1.1.0.alpha.3'
  gem "compass-rails", :path=>"."
  gem 'compass-blueprint'
end

group :test do
  gem 'mocha'
  gem "appraisal", :git => 'https://github.com/scottdavis/appraisal.git'
  gem 'rainbow'
end

unless ENV["CI"]
  gem 'rb-fsevent', :require => false
  gem 'ruby_gntp', :require => false
  gem 'guard'
  gem 'guard-test'
end
