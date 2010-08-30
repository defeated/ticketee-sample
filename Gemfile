source 'http://rubygems.org'

gem 'rails',        '3.0.0'
gem 'sqlite3-ruby', :require => 'sqlite3'

group :test do
  gem 'rspec-rails', '~>2.0.0.beta.20'
end

# The cucumber group is an exception to this group-environment relationship:
# it is not a Rails environment. We place the requirements inside the group
# so that the gems are made available to be loaded, but are not required
# automatically by the config/application.rb Bundler.require call. The
# Cucumber and Cucumber-related gems are required by the require calls at
# the beginning of features/support/env.rb.
group :cucumber do
  gem 'cucumber-rails'
  gem 'capybara'
end