source 'https://rubygems.org'

gemspec

if Gem::Version.new(RUBY_VERSION) >= Gem::Version.new('1.9')
  gem 'codeclimate-test-reporter', :group => :test, :require => nil
end

if ENV['RAILS_VERSION']
  gem 'rails', ENV['RAILS_VERSION']
  # Temporary restrict sprockets-rails version
  # TODO: adapt railtie for sprockets-rails 3.0
  gem 'sprockets-rails', '< 3'
end
